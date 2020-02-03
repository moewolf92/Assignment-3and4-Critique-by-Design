# Assignment-3and4-Critique-by-Design
## Assignment-3-4-Critique-by-Design

#so I am interested in healthcare, so I searched the CDC’s website for some graphs I could improve upon. I found some on health insurance coverage, race, and year that I thought could be redone to be more visually enticing and tell a better story. 

#https://www.cdc.gov/nchs/ppt/hus/hus18fig20.pptx

#https://www.cdc.gov/nchs/data/hus/2018/fig20.pdf

#https://ftp.cdc.gov/pub/Health_Statistics/NCHS/Publications/Health_US/hus18figures/fig20.xlsx

#Observations of the data: I found that the first graphic could easily be made into a stacked area chart and be made much more intuitive. The second chart doesn't lend itself well to making comparisons between races, I think there is a larger relationship between the types of health insurance hispanics and blacks have, and clustering them together would help illuminate the difficulties those races face. The charts are also not visually exciting or engaging, and the title is quite wordy. The colors could be more exciting, I feel. 

#Who is the primary audience for this tool? Do you think this visualization is effective for reaching that audience? Why or why not? I think the primary audience for this visualization might be healthcare professionals, administration or insurance execs, or students. This visualization is relatively effective, but only for reaching that audience. This kind of visualization is a very hot topic, and having a compelling visualization from the CDC itself might have been useful in political campaigns and health insurance discussions. 

#It was an interrelated group of 2 graphs, so I decded to do both, although, in hindsight, I probably should’ve just stuck to the second, which is where I saw more opportunity. The first chart was a chart on how insurance coverage has changed from 2007 to 2018. The second was a graph of the different types of insurance coverage people of different races had in 2017. The data on the first chart was just presented in a line graph, which I didn’t think was very clear or compelling, and the second graph didn’t effectively show the disparities between races, so I took to recreating them both. 

#I use powerpoint to create almost all my graphs for several reasons. It is able to create clear, nice looking graphs quite easily; it integrates well with excel, which is good for simple data analysis, which is what I do most of the time; it can auto-create graphs based on the data fed into it (though they always need to be fine-tuned), the graphs can be edited by a lay person with no coding skills, which is great when you want someone else to work on your graphs as well, and almost everyone I know has the Microsoft office suite on their computer. 

#The first iteration of the first chart was a stacked area chart. This proved to be confusing for both my testers, as they saw the lower areas  as having less than the higher areas, because they pictured it as a sort of series of half full pictures layered on top of one another. So using this feedback, I switched to a bar chart and labeled the percentages on each bar. It’s not as neat as the stacked area chart, but it does look better than the original, and it is clearer as well, at least from my users input. I had immediate understanding for the second chart, so I pretty much left it as is. 
<!DOCTYPE html>
<html lang="en">
<head>
<!-- v1.7.0 -->
<meta http-equiv="X-UA-Compatible" content="IE=Edge" />
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title></title>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.1/css/font-awesome.min.css">
<link rel="stylesheet" type="text/css" href="assets/idrviewer.css">
<script src="assets/idrviewer.js" type="text/javascript"></script>
<script src="assets/idrviewer.querystring-navigation.js"></script>
<script src="assets/idrviewer.fullscreen.js"></script>
<script src="assets/idrviewer.search.js"></script>
<script src="assets/idrviewer.annotations.js"></script>
<script type="text/javascript">
(function() {
    "use strict";
    var LanguageHelper = (function() {
        var translationsList = {
            "ja":{"control.sidebar": "サイドバー","control.theme-toggle": "テーマ切換","control.prev": "前のページ",
                "control.next": "次のページ","control.select": "選択","control.move": "パン","control.zoom-out": "縮小",
                "control.zoom-in": "拡大","control.actual-size": "実際のサイズ","control.fit-width": "幅に合わせる",
                "control.fit-height": "高さに合わせる","control.fit-page": "ページに合わせる","control.auto": "自動",
                "control.fullscreen": "フルスクリーン","control.thumbnails": "サムネイル","control.outlines": "ブックマーク",
                "control.presentation": "プレゼンテーション","control.magazine": "マガジン","control.continuous": "スクロール",
                "control.search": "検索","control.page": "ページ","search.search": "検索","search.match-case": " 大文字・小文字を区別",
                "search.limit-results-1": " 結果を1ページ１つに制限する","search.limit-results-500": "最初の500件が表示されます。",
                "search.results-count": " 件","search.unavailable": "検索できません","search.loading": "ローディング"},
            "fr":{"control.sidebar": "Barre latérale","control.theme-toggle": "Basculer entre les thèmes","control.prev": "Page précédente",
                "control.next": "Page suivante","control.select": "Sélectionner","control.move": "Déplacer","control.zoom-out": "Zoom arrière",
                "control.zoom-in": "Zoom avant","control.actual-size": "Taille réelle","control.fit-width": "Pleine largeur",
                "control.fit-height": "Pleine hauteur","control.fit-page": "Page entière","control.auto": "Automatique",
                "control.fullscreen": "Plein écran","control.thumbnails": "Vignettes","control.outlines": "Signets",
                "control.presentation": "Présentation","control.magazine": "Magazine","control.continuous": "En continu",
                "control.search": "Recherche","control.page": "Page","search.search": "Rechercher","search.match-case": " Respecter la casse",
                "search.limit-results-1": " Limiter les résultats à 1 par page","search.limit-results-500": "Limitée aux 500 premiers résultats",
                "search.results-count": " résultats","search.unavailable": "Recherche non accessible","search.loading": "Chargement en cours"},
            "de":{"control.sidebar": "Seitenleiste","control.theme-toggle": "Darstellung wechseln","control.prev": "Vorherige Seite",
                "control.next": "Nächste Seite","control.select": "Auswählen","control.move": "Bewegen","control.zoom-out": "Zoom Out",
                "control.zoom-in": "Zoom In","control.actual-size": "Tatsächliche Grösse","control.fit-width": "Breite füllend",
                "control.fit-height": "Höhe füllend","control.fit-page": "Seite füllend","control.auto": "Automatisch",
                "control.fullscreen": "Ganzer Bildschirm","control.thumbnails": "Mini-Ansichten","control.outlines": "Lesezeichen",
                "control.presentation": "Präsentationsdarstellung","control.magazine": "Magazindarstellung",
                "control.continuous": "Fortlaufende Darstellung","control.search": "Suchen","control.page": "Seite","search.search": "Suchen",
                "search.match-case": "Gross-/Kleinschreibung beachten","search.limit-results-1": "Auf 1 Resultat pro Seite begrenzen",
                "search.limit-results-500": "Auf die ersten 500 Resultate begrenzen.","search.results-count": " Resultat(e)",
                "search.unavailable": "Suche nicht verfügbar.","search.loading": "Lade"},
            "hi":{"control.sidebar": "साइडबार","control.theme-toggle": "विषय टॉगल","control.prev": "पिछला पृष्ठ",
                "control.next": "अगला पृष्ठ","control.select": "चुनते हैं","control.move": "पान","control.zoom-out": "छोटा करें",
                "control.zoom-in": "बड़ा करें","control.actual-size": "वास्तविक आकार","control.fit-width": "चौड़ाई पर फ़िट",
                "control.fit-height": "ठीक ऊंचाई","control.fit-page": "फिट पेज","control.auto": "स्वचालित",
                "control.fullscreen": "पूर्ण स्क्रीन","control.thumbnails": "थंबनेल","control.outlines": "बुकमार्क",
                "control.presentation": "प्रदर्शन","control.magazine": "पत्रिका",
                "control.continuous": "निरंतर","control.search": "खोज","control.page": "पृष्ठ","search.search": "खोज",
                "search.match-case": "मिलान घटना","search.limit-results-1": "सीमा परिणाम 1 प्रति पृष्ठ",
                "search.limit-results-500": "पहले 500 परिणामों तक सीमित है","search.results-count": " परिणाम",
                "search.unavailable": "उपलब्ध नहीं खोजें।","search.loading": "लोड हो रहा है"}
        };

        var lang = (navigator.language || navigator.userLanguage).substr(0, 2);
        var translations = translationsList[lang] ? translationsList[lang] : false;

        return {
            getTranslation: function(name) {
                return translations ? translations[name] : null;
            },

            updateElements: function() {
                if (translations) {
                    document.documentElement.setAttribute("lang", lang);
                    var i, element;
                    var titleElements = document.querySelectorAll("[data-lang-title]");
                    for (i = 0; i < titleElements.length; i++) {
                        element = titleElements[i];
                        if (translations[element.dataset.langTitle]) {
                            element.title = translations[element.dataset.langTitle];
                        }
                    }
                    var textElements = document.querySelectorAll("[data-lang-text]");
                    for (i = 0; i < textElements.length; i++) {
                        element = textElements[i];
                        if (translations[element.dataset.langText]) {
                            element.innerText = translations[element.dataset.langText];
                        }
                    }
                }
            }
        };
    })();

    var Button = {},
        pageLabels = [];

    /**
     * Shorthand helper function to getElementById
     * @param id
     * @returns {Element}
     */
    var d = function (id) {
        return document.getElementById(id);
    };

    var ClassHelper = (function() {
        return {
            addClass: function(ele, name) {
                var classes = ele.className.length !== 0 ? ele.className.split(" ") : [];
                var index = classes.indexOf(name);
                if (index === -1) {
                    classes.push(name);
                    ele.className = classes.join(" ");
                }
            },

            removeClass: function(ele, name) {
                var classes = ele.className.length !== 0 ? ele.className.split(" ") : [];
                var index = classes.indexOf(name);
                if (index !== -1) {
                    classes.splice(index, 1);
                }
                ele.className = classes.join(" ");
            },

            toggleClass: function(ele, name) {
                var classes = ele.className.length !== 0 ? ele.className.split(" ") : [];
                var index = classes.indexOf(name);
                var wasClassAdded;
                if (index === -1) {
                    classes.push(name);
                    wasClassAdded = true;
                } else {
                    classes.splice(index, 1);
                    wasClassAdded = false;
                }
                ele.className = classes.join(" ");
                return wasClassAdded;
            }
        };
    })();

    /**
     * Encapsulation of sidebar functionality
     */
    var Sidebar = (function () {

        var Sidebar = {},
            loadedThumbsArray = [],
            thumbnailPositions = [],
            lastScroll = 0,
            sidebar,
            thumbnailBar,
            imageType,
            scrollSidebar = true,
            thumbnailPanel,
            bookmarkPanel,
            searchPanel,
            isSearchLoaded,
            searchInput,
            thumbnailScrollPt = 0,
            bookmarkScrollPt = 0,
            searchScrollPt = 0,
            curPg,
            pgCount,
            MAX_THUMBNAIL_WIDTH = 160,
            MAX_THUMBNAIL_HEIGHT = 200;

        /**
         * Performs the setup for the sidebar
         * @param initialPage Current page
         * @param pageCount Page count
         * @param bounds Page bounds array
         * @param thumbnailType Image type used for thumbnails
         * @param bookmarks Object containing any bookmarks
         */
        Sidebar.setup = function (initialPage, pageCount, bounds, thumbnailType, bookmarks) {

            curPg = initialPage;
            pgCount = pageCount;
            Button.outlines = d('btnOutlines');
            Button.thumbnails = d('btnThumbnails');
            Button.search = d('btnSearch');
            d('btnSideToggle').onclick = Sidebar.toggleSidebar;
            Button.outlines.onclick = Sidebar.switchToBookmarks;
            Button.thumbnails.onclick = Sidebar.switchToThumbnails;
            Button.search.onclick = Sidebar.switchToSearch;

            thumbnailBar = d('leftContent');
            sidebar = d('left');
            thumbnailPanel = d('thumbnailPanel');
            bookmarkPanel = d('outlinePanel');
            searchPanel = d('searchPanel');
            searchInput = d('searchInput');
            imageType = thumbnailType;

            loadThumbnailFrames(bounds);
            // Initialise loaded array
            for (var i = 0; i < pgCount; i++) {
                loadedThumbsArray[i] = false;
            }

            Sidebar.switchToThumbnails();

            thumbnailBar.addEventListener("scroll", handleThumbnailBarScroll);

            if (bookmarks.length > 0) {
                Sidebar.setBookmarks(bookmarks);
            }
            bookmarkScrollPt = bookmarkPanel.scrollTop;
            searchScrollPt = searchPanel.scrollTop;
            thumbnailBar.scrollTop = thumbnailScrollPt;

            searchInput.value = LanguageHelper.getTranslation("search.loading") || "Loading";
            searchInput.disabled = "disabled";
            searchInput.oninput = doSearch;
            d('cbMatchCase').onclick = doSearch;
            d('cbLimitResults').onclick = doSearch;

            document.addEventListener('keydown', function(event) {
                if (event.keyCode == 70 && (event.ctrlKey || event.metaKey)) {
                    Sidebar.openSidebar();
                    Sidebar.switchToSearch();
                    event.preventDefault();
                }
            });
        };

        var doSearch = function() {
            var resultDiv = document.getElementById('searchResults');
            resultDiv.innerHTML = "";

            var searchTerm = d('searchInput').value;
            var matchCase = d('cbMatchCase').checked;
            var limitOnePerPage = d('cbLimitResults').checked;

            var results = IDRViewer.search(searchTerm, matchCase, limitOnePerPage);

            d('searchResultsCount').innerHTML = String(results.length) + (LanguageHelper.getTranslation("search.results-count") || " results");

            var docFrag = document.createDocumentFragment();
            for (var i = 0; i < results.length && i < 500; i++) {
                var pg = results[i].page;

                var link = document.createElement("a");
                link.href = "?page=" + pg;
                link.innerHTML = results[i].snippet;
                link.className = "result";
                (function(page) {
                    link.onclick = function() {
                        IDRViewer.goToPage(page);
                        return false;
                    };
                })(pg);

                docFrag.appendChild(link);

            }
            if (results.length >= 500) {
                var element = document.createElement("span");
                element.innerHTML = LanguageHelper.getTranslation("search.limit-results-500") || "Limited to first 500 results.";
                element.className = "result";
                docFrag.appendChild(element);
            }
            resultDiv.appendChild(docFrag);
        };

        Sidebar.openSidebar = function() {
            if (sidebar.className.indexOf("open") === -1) {
                Sidebar.toggleSidebar();
            }
        };

        /**
         * Toggle the sidebar open and closed
         */
        Sidebar.toggleSidebar = function () {
            if (ClassHelper.toggleClass(sidebar, "open")) {
                loadVisibleThumbnails();
            }
        };

        /**
         * Display the thumbnail panel in the sidebar
         */
        Sidebar.switchToThumbnails = function () {
            if (bookmarkPanel.className == "visible") {
                bookmarkScrollPt = thumbnailBar.scrollTop;
            }
            if (searchPanel.className == "visible") {
                searchScrollPt = thumbnailBar.scrollTop;
            }

            thumbnailPanel.className = "visible";
            bookmarkPanel.className = "hidden";
            searchPanel.className = "hidden";
            if (sidebar.className.indexOf("open") !== -1) {
                loadVisibleThumbnails();
                updateThumbnailPanelToCurrentPage();
            }
            Button.thumbnails.className = 'disabled btn';
            Button.outlines.className = 'btn';
            Button.search.className = 'btn';
        };

        /**
         * Display the bookmarks panel in the sidebar
         */
        Sidebar.switchToBookmarks = function () {
            if (searchPanel.className == "visible") {
                searchScrollPt = thumbnailBar.scrollTop;
            }
            if (thumbnailPanel.className == "visible") {
                thumbnailScrollPt = thumbnailBar.scrollTop;
            }

            thumbnailPanel.className = "hidden";
            bookmarkPanel.className = "visible";
            searchPanel.className = "hidden";
            Button.thumbnails.className = 'btn';
            Button.outlines.className = 'disabled btn';
            Button.search.className = 'btn';
            thumbnailBar.scrollTop = bookmarkScrollPt;
        };

        Sidebar.switchToSearch = function() {
            if (bookmarkPanel.className == "visible") {
                bookmarkScrollPt = thumbnailBar.scrollTop;
            }
            if (thumbnailPanel.className == "visible") {
                thumbnailScrollPt = thumbnailBar.scrollTop;
            }

            thumbnailPanel.className = "hidden";
            bookmarkPanel.className = "hidden";
            searchPanel.className = "visible";
            Button.thumbnails.className = 'btn';
            Button.outlines.className = 'btn';
            Button.search.className = 'disabled btn';

            var loadListener = function(loaded) {
                if (loaded) {
                    searchInput.value = "";
                    searchInput.disabled = "";
                    searchInput.focus();
                } else {
                    searchInput.value = LanguageHelper.getTranslation("search.unavailable") || "Search not available.";
                }
            };
            var progressListener = function(percentageLoaded) {
                searchInput.value = (LanguageHelper.getTranslation("search.loading") || "Loading") + " (" + percentageLoaded + "%)";
            };
            if (!isSearchLoaded) {
                IDRViewer.loadSearch(loadListener, progressListener);
            }
            searchInput.focus();
            thumbnailBar.scrollTop = searchScrollPt;
        };

        /**
         * Load the frames for all the thumbnails
         * @param bounds Page bound array
         */
        var loadThumbnailFrames = function (bounds) {
            var heights = [];
            // Calculate height for max width of 160px and max height of 200px
            for (var i = 0; i < bounds.length; i++) {
                var height = Math.floor(bounds[i][1] * (MAX_THUMBNAIL_WIDTH / bounds[i][0]));
                heights[i] = (bounds[i][0] > bounds[i][1] || height <= MAX_THUMBNAIL_HEIGHT) ? height : MAX_THUMBNAIL_HEIGHT;
            }

            function makeThumbnailClickHandler(pg) {
                return function() {
                    scrollSidebar = false;
                    IDRViewer.goToPage(pg);
                    return false;
                };
            }

            for (var page = 1; page <= bounds.length; page++) {
                var ele = document.createElement("a");
                ele.style.height = heights[page - 1] + "px";
                ele.className = "thumbnail";
                ele.href = "?page=" + page;
                ele.id = "thumb" + page;
                ele.onclick = makeThumbnailClickHandler(page);
                ele.setAttribute('title', (LanguageHelper.getTranslation("control.page") || 'Page') + ' ' + page);
                var margin = Math.floor((heights[page - 1] - 42) / 2);
                ele.innerHTML = '<div class="spinner" style="margin-top: ' + margin + 'px;"></div>';
                thumbnailPanel.appendChild(ele);
            }

            for (page = 1; page <= bounds.length; page++) {
                thumbnailPositions[page - 1] = thumbnailPanel.children[page - 1].offsetTop;
            }
        };

        var handleThumbnailBarScroll = function () {
            var scrollTop = thumbnailBar.scrollTop;
            lastScroll = scrollTop;
            showVisibleSpinners();
            setTimeout(function () {
                loadVisibleThumbnails(scrollTop);
            }, 500);
        };

        var showVisibleSpinners = function() {
            var startY = thumbnailBar.scrollTop;
            var endY = startY + thumbnailBar.clientHeight;
            for (var index = 0; index < pgCount; index++) {
                if (!loadedThumbsArray[index]) {
                    if (thumbnailPositions[index] + MAX_THUMBNAIL_WIDTH > startY && thumbnailPositions[index] < endY) {
                        ClassHelper.addClass(thumbnailPanel.children[index].firstChild, "spinning");
                    } else {
                        ClassHelper.removeClass(thumbnailPanel.children[index].firstChild, "spinning");
                    }
                }
            }
        };

        var loadVisibleThumbnails = function (scrollTop) {
            if (typeof scrollTop !== 'undefined' && scrollTop != lastScroll)
                return;

            // load thumbs in view
            for (var thumbIndex = 0; thumbIndex < pgCount; thumbIndex++) {
                if (!loadedThumbsArray[thumbIndex]) {
                    var curThumb = thumbnailPanel.children[thumbIndex];
                    // Bails out of the loop when the next thumbnail is below the viewable area
                    if (curThumb.offsetTop > thumbnailBar.scrollTop + thumbnailBar.clientHeight) {
                        break;
                    }
                    if (curThumb.offsetTop + curThumb.clientHeight > thumbnailBar.scrollTop) {
                        curThumb.innerHTML = '<img src="thumbnails/' + (thumbIndex + 1) + '.' + imageType + '" />';
                        loadedThumbsArray[thumbIndex] = true;
                    }
                }
            }
        };

        /**
         * Scrolls the thumbnail bar to a specific page and adds currentPageThumbnail class.
         * @param page Page to scroll to
         */
        Sidebar.handlePageChange = function (page) {
            curPg = page;
            if (thumbnailPanel.className === "visible") {
                updateThumbnailPanelToCurrentPage();
            }
            scrollSidebar = true;
        };

        var updateThumbnailPanelToCurrentPage = function() {
            var curThumb = thumbnailPanel.children[curPg - 1];
            if (curThumb.className !== "thumbnail currentPageThumbnail") {

                for (var i = 0; i < pgCount; i++) {
                    thumbnailPanel.children[i].className = "thumbnail";
                }

                curThumb.className = "thumbnail currentPageThumbnail";

                if (scrollSidebar) {
                    thumbnailBar.scrollTop = thumbnailBar.scrollTop + curThumb.getBoundingClientRect().top - d('leftContent').getBoundingClientRect().top;
                }
            }
        };

        Sidebar.setBookmarks = function (bookmarks) {
            ClassHelper.addClass(sidebar, 'hasBookmarks');
            addBookmark(bookmarkPanel, bookmarks);
        };

        var addBookmark = function (container, bookmarks) {
            var outer = document.createElement('ul');

            var makeBookmarkClickHandler = function(pg, zoom) {
                return function() {
                    IDRViewer.goToPage(parseInt(pg), zoom);
                };
            };
            for (var i = 0; i < bookmarks.length; i++) {
                var bookmark = bookmarks[i];
                var li = document.createElement('li');
                li.setAttribute('title', 'Page ' + bookmark.page);
                li.innerHTML = bookmark.title;
                li.onclick = makeBookmarkClickHandler(bookmark.page, bookmark.zoom);
                outer.appendChild(li);
                if (typeof(bookmark.children) != 'undefined') {
                    addBookmark(outer, bookmark.children);
                }
            }
            container.appendChild(outer);
        };

        return Sidebar;
    })();

    var populateGoBtn = function (initialPage, pgCount) {
        Button.go.className = "";
        Button.go.innerHTML = "";
        for (var i = 1; i <= pgCount; i++) {
            var opt = document.createElement('option');
            opt.value = i;
            opt.innerHTML = pageLabels.length ? pageLabels[i - 1] : String(i);
            Button.go.appendChild(opt);
        }
        Button.go.selectedIndex = initialPage - 1;
    };

    var handleGoBtn = function () {
        IDRViewer.goToPage(parseInt(Button.go.options[Button.go.selectedIndex].value));
        this.blur();
    };

    var updateSelectionButtons = function (mode) {
        switch (mode) {
            case IDRViewer.SELECT_PAN:
                Button.select.className = 'btn';
                Button.move.className = 'disabled btn';
                break;
            case IDRViewer.SELECT_SELECT:
                Button.select.className = 'disabled btn';
                Button.move.className = 'btn';
                break;
        }
    };

    var handlePageChange = function (data) {
        d('pgCount').innerHTML = getPageString(data.page, data.pagecount);
        Sidebar.handlePageChange(data.page);
        Button.go.selectedIndex = data.page - 1;

        Button.prev.className = data.isFirstPage ? 'disabled btn' : 'btn';
        Button.next.className = data.isLastPage ? 'disabled btn' : 'btn';
    };

    var handleZoomUpdate = function (data) {
        Button.zoom.value = data.zoomType;
        Button.zoom.options[0].innerHTML = Math.floor(data.zoomValue * 100) + "%";

        Button.zoomOut.className = data.isMinZoom ? 'disabled btn' : 'btn';
        Button.zoomIn.className = data.isMaxZoom ? 'disabled btn' : 'btn';
    };

    var handleSelectionChange = function (data) {
        updateSelectionButtons(data.type);
    };

    var handleZoomBtn = function () {
        var zoomType = Button.zoom.value;
        if (zoomType != IDRViewer.ZOOM_SPECIFIC) {
            IDRViewer.setZoom(zoomType);
        }
        this.blur();
    };

    var handleViewBtn = function () {
        IDRViewer.setLayout(Button.View.value);
        this.blur();
    };

    var setupLayoutSwitching = function (pgCount, layout, availableLayouts) {
        if (availableLayouts.length > 1 && pgCount > 1) {
            Button.View = document.createElement('select');
            Button.View.id = 'viewBtn';

            var temp = document.createElement('option');
            temp.innerHTML = LanguageHelper.getTranslation("control.presentation") || "Presentation";
            temp.value = IDRViewer.LAYOUT_PRESENTATION;
            Button.View.appendChild(temp);

            if (availableLayouts.indexOf(IDRViewer.LAYOUT_MAGAZINE) != -1) {
                temp = document.createElement('option');
                temp.innerHTML = LanguageHelper.getTranslation("control.magazine") || "Magazine";
                temp.value = IDRViewer.LAYOUT_MAGAZINE;
                Button.View.appendChild(temp);
            }
            if (availableLayouts.indexOf(IDRViewer.LAYOUT_CONTINUOUS) != -1) {
                temp = document.createElement('option');
                temp.innerHTML = LanguageHelper.getTranslation("control.continuous") || "Continuous";
                temp.value = IDRViewer.LAYOUT_CONTINUOUS;
                Button.View.appendChild(temp);
            }
            Button.View.onchange = handleViewBtn;
            d('controls-center').appendChild(Button.View);
            Button.View.value = layout;
        }
    };

    var handleFullscreenChange = function (data) {
        if (data.isFullscreen) {
            Button.fullscreen.className = "btn open";
        } else {
            Button.fullscreen.className = "btn closed";
        }
    };

    function getPageString(page, pageCount) {
        var result = "/ " + pageCount;
        if (pageLabels.length) {
            result =  "(" + page + " / " + pageCount + ")";
        }
        return result;
    }

    function swapNavButtonsForR2L() {
        Button.next.parentNode.insertBefore(Button.prev, Button.next);
        Button.prev.parentNode.insertBefore(Button.next, Button.prev.parentNode.firstChild);
        var nextInnerHtml = Button.next.innerHTML;
        Button.next.innerHTML = Button.prev.innerHTML;
        Button.prev.innerHTML = nextInnerHtml;
    }

    /**
     * Main setup function that runs on load
     */
    IDRViewer.on('ready', function (data) {
        LanguageHelper.updateElements();

        // Grab buttons
        Button.go = d('goBtn');
        Button.zoom = d('zoomBtn');
        Button.fullscreen = d('btnFullScreen');
        Button.prev = d('btnPrev');
        Button.next = d('btnNext');
        Button.move = d('btnMove');
        Button.select = d('btnSelect');
        Button.zoomIn = d('btnZoomIn');
        Button.zoomOut = d('btnZoomOut');

        Button.prev.className = data.isFirstPage ? 'disabled btn' : 'btn';
        Button.next.className = data.isLastPage ? 'disabled btn' : 'btn';

        // Set button actions
        Button.go.onchange = handleGoBtn;
        Button.zoom.onchange = handleZoomBtn;
        Button.prev.onclick = function (e) { IDRViewer.prev(); e.preventDefault(); };
        Button.next.onclick = function (e) { IDRViewer.next(); e.preventDefault(); };
        Button.move.onclick = function (e) { IDRViewer.setSelectMode(IDRViewer.SELECT_PAN); e.preventDefault(); };
        Button.select.onclick = function (e) { IDRViewer.setSelectMode(IDRViewer.SELECT_SELECT); e.preventDefault(); };
        Button.zoomIn.onclick = function (e) { IDRViewer.zoomIn(); e.preventDefault(); };
        Button.zoomOut.onclick = function (e) { IDRViewer.zoomOut(); e.preventDefault(); };

        if (data.isR2L) {
            swapNavButtonsForR2L();
        }

        document.onkeydown = function (e) {
            switch (e.keyCode) {
                case 33: // Page Up
                    IDRViewer.prev();
                    e.preventDefault();
                    break;
                case 34: // Page Down
                    IDRViewer.next();
                    e.preventDefault();
                    break;

                case 37: // Left Arrow
                    data.isR2L ? IDRViewer.next() : IDRViewer.prev();
                    e.preventDefault();
                    break;
                case 39: // Right Arrow
                    data.isR2L ? IDRViewer.prev() : IDRViewer.next();
                    e.preventDefault();
                    break;

                case 36: // Home
                    IDRViewer.goToPage(1);
                    e.preventDefault();
                    break;
                case 35: // End
                    IDRViewer.goToPage(data.pagecount);
                    e.preventDefault();
                    break;
            }
        };

        // Misc setup
        document.title = data.title ? data.title : data.fileName;
        updateSelectionButtons(data.selectMode);
        pageLabels = data.pageLabels;

        populateGoBtn(data.page, data.pagecount);

        Sidebar.setup(data.page, data.pagecount, data.bounds, data.thumbnailType, data.bookmarks);
        d('pgCount').innerHTML = getPageString(data.page, data.pagecount);

        if (IDRViewer.isFullscreenEnabled()) {
            Button.fullscreen.onclick = function () {
                IDRViewer.toggleFullScreen();
            };
            IDRViewer.on('fullscreenchange', handleFullscreenChange);
        } else {
            Button.fullscreen.parentNode.removeChild(Button.fullscreen);
        }

        if (data.isMobile) {
            ClassHelper.addClass(document.body, "is-mobile");
        }
        setupLayoutSwitching(data.pagecount, data.layout, data.availableLayouts);
        Button.zoom.value = IDRViewer.ZOOM_AUTO;

        // Add event listeners
        IDRViewer.on('selectchange', handleSelectionChange);
        IDRViewer.on('pagechange', handlePageChange);
        IDRViewer.on('zoomchange', handleZoomUpdate);

        var themeToggle = false;
        d('btnThemeToggle').addEventListener('click', function() {
            ClassHelper.removeClass(document.body, "light-theme");
            ClassHelper.removeClass(document.body, "dark-theme");
            ClassHelper.addClass(document.body, themeToggle ? "light-theme" : "dark-theme");
            themeToggle = !themeToggle;
        });

        (function reticulateSplines() {
            var el = document.createElement("div");
            el.innerHTML = atob("PGRpdiBzdHlsZT0icG9zaXRpb246Zml4ZWQ7cmlnaHQ6MzBweDtib3R0b206MTVweDtib3JkZXItcmFkaXVz" +
              "OjVweDtib3gtc2hhZG93OiAxcHggMXB4IDRweCByZ2JhKDEyMCwxMjAsMTIwLDAuNSk7bGluZS1oZWlnaHQ6MDtvdmVyZmxvdzpoaW" +
              "RkZW47Ij48YSBocmVmPSJodHRwczovL3d3dy5pZHJzb2x1dGlvbnMuY29tL2J1aWxkdnUvIiByZWw9Im5vZm9sbG93IiB0YXJnZXQ9" +
              "Il9ibGFuayI+PGltZyBhbHQ9IkNyZWF0ZWQgd2l0aCBCdWlsZFZ1IiBzdHlsZT0iYm9yZGVyOjA7IiBzcmM9ImRhdGE6aW1hZ2UvcG" +
              "5nO2Jhc2U2NCxpVkJPUncwS0dnb0FBQUFOU1VoRVVnQUFBSllBQUFBdENBTUFBQUI3MG1KbUFBQUNQVkJNVkVYLy8vLysvdjBkSFJ2" +
              "NysvdjgvUHlJaUlmYjI5di9iMG41d3k3MzkvZjR3aXY0d1NscWFtcng4ZkcwdExQNHZ5WGw1ZVhnNE9EQ3dzSjRlSGR1Ym0zVDA5UD" +
              "R3Q2YzdmlQZTN0MnhzYkZnWUYvNHdpMzN2Qi9yNit1aG9hQ0VoSU9CZ1lCeGNYQlpXVmZvNk9oUlVWRkRRMElwS1NqajQrTm9hR2Ri" +
              "VzFvbEpTUDN1Qlh6OC9QS3lzcGRYVjFKU1VjOFBEdjJ0USs2dXJxNHVMZGtaR1JVVkZQL2NFcjJ1aG42K3ZxcXFxcW1wcVpMUzBwQl" +
              "FUODRPRGI1K2ZuMTlmWFgxOWZIeDhlK3ZyMmVucDZhbXBxWGw1ZU9qbzU4Zkh0MWRYVnpjM05XVmxaSFIwWGxueDM0dXh6Ky9mcnQ3" +
              "ZTMrK2V2aTR1TFkyTmpRME5ERnhjV3VycTJVbEpSUFQwNGdJQi9uNStmT3pzN0J3Y0g4NTYraW9xS0tpb241MG12K256ejltVHMwTk" +
              "RMNHdqSDR2aUhub3lIbm9CLzJ1aHZqblJqZ21CUCsvdnorOE16TXpNejk3Y1gvd0svODVxaWpvNk9Sa1pIL2JVcitxajMrcFQzOGp6" +
              "VXRMU3p1cWgvMXNnais5K1RhMnRyLzI5TC8xc3ovekwvNzNJYUdob1g2Mm9INTBGMzV6RTcvYzA3K2wwSDV5RUQ5a1VEK2RrRC9zRH" +
              "ozeER2OGtqbi93RGoxdVNULysvcisrdkgvOU9ycTZ1ci83T2YvNXQvKzg5Zjg2cjM4NDUveDBwai9wby80eTRML2tYVDUwV1AvZzJI" +
              "NXlVVC9uMFQrYjBQL3REdit0emZ5cERMOGhUTDRzaTdycENJYkd4dnlyeGIvOXZQKzZ0ajk4dFAvMWNyNDU4bisyOFgrM2NQOTRxMy" +
              "91cWYvdUtUKzE1di9ycGo3NEpYL25JTDlwNEQ1MVh6NjFXL3N3R3Y3cm1UK3RtUCtrMkg5cDFQbXFUdnpxQzZaVVdMMEFBQUdYVWxF" +
              "UVZSWXcrMlloMTlTVVJUSHo3czg1WUdBVEJOSUJRRVZBeVFRVXlRMTl5cHpsWmxsYXBxMmQ3YjMzbnZ2dmZjZWYxdm52aWRGRmlPcl" +
              "QzMCsrZnZvdS9kdzEvZWRjKzY5ZklCUmplcS9GQU0vcS9nNEVNRWYxbno0SjdFNnB3SXdJOGRpWWd3SU04eUtOdmJDemdYWTRSZThs" +
              "YW53ZXpKeENvYmgvN0Vtck12Q1YzdFdLaTJEVkFVZW9DcjNSM0Q2Sm83cndMNGp4bHBxelRMWFZuNDNmK1BDVU11d05OUzdGWDVITT" +
              "lZTU15RzhPamlPMnpSU2I3R2djSy9EMHNIS1U5U1pvUFNrQUJRN25RQ1Fwbld3WVBGWXFEdWJVM0piRUVPT2RRbEFBeXVCU3ExU1ZH" +
              "VExkRnJDK3VNNDE4TnhXNmVHdGs5aFl2ZVd6Y2w3UU9Lck5hUjZDbVcyaGFETjlhV0Q0cWJiS3ZlaVBRbVdXYXRzMHhGWGJpc0Nsd2" +
              "JhZlpiY1NXM2Q2ZTNLREUzV3hKSndYRk8zY2FnTDN5WVlFeXRXUzdxRUwyZGs2MENIaTgvV1VxdFd6ZFlXbzIyQlpUVmVxd2owTGtB" +
              "djVzaWJNdXdnbTlXY0pkRmlpQXNNREdncmdRMnpTMTV6bk5GbzdGbnlsZWdNWll3TlM1OHJkQ3kxQTB6TE1NWFovVkJRWXk1c2pMZG" +
              "lTbWVZTnJ2OHVXcUFzaG9BeUhlcHFzczFTaXRVVk1UTDBIdWFWQUN6Tit4Q0p4RkxhcFJ5VzRKNzkxVC8va1ZZeG9SVkVwRHo1YlE0" +
              "VEtmcWZDWDZ5enlqTkFkbXpRYUlNNlBOMU1WanJZTE9iWkxGWmNhNVVrSG1VVlBNNlpodk5tWFlkUmIxY0ZLcE5FRnEzTHFXdCs4UE" +
              "RGemYvNGh5UmNkaXdHeFhNVTFPTUhnQnZMWWpUQU5NTDhOc0FuTVplakJnZ1JUUVZrTjdZUXVncW02cXdMNWFCTlltdnd4RWpweEdp" +
              "QThBS214eUdSRXJJVUc2Y3hHYWh6NE9ES3paZitVcFFFeFlZSExKWEV1aDJrSTNmcnFoSE5RK1U1eVptZW5US3FFODNWQUJTb05Nby" +
              "tWZDZ0K01ma3VGaGtwSGsxV1duRm5wQU9leUNDZndPYzZJVkVsSkNVbFNUTEEzOWYwRGZWY3U3emt6SlRvV3o2WFVLVEdmaFdvSnJt" +
              "OVJnVHdmVkNWRnVCR296ZW9hdnZTbDQxZ0o5dEZKV0d3dnlvOXdKejRYc0JJVEU1T1NOcDJxcjYvdjc3OStlYytLZDRlQm50c1JzTD" +
              "dmdVZHMk14T3RRMmpiQXNTaVZHTlFpUWQ2Ni92cSt6L3RXYkZ5em9jN2YrK3FSazNaeXcxaHpSMDdkdTZCTlgxOTlUZFdJRmJYam9l" +
              "d2VNTmZ3NEpPQVl0U1RaNDNlY0thdnQ3ZWxTdm56T2xhdGVybDh1M3JnWW1LeGJBUjRqR3lucWlUUVN5a21qQmgzTGhidmIxWEw4N3" +
              "AycmZxMmlXeE9HL0RuL0FXRTBPQzNlV01OT1hIVUdjaDFmanh0MjVjdmJpamE5KzFTM2xpc1hqN3ZVaFg5YlJBbmRzZE1IalF5S3kx" +
              "NmVnOVpMQ3BBU1JWYmdVdTJWN25VdzVsZXBtdExoREkwVFJqblFGOWhjQlRVSTZQNU0yODRkQU9QN21NMGlFc1NvVWFYTk8xWTllcT" +
              "NjdkZxRHp4UnB6cHgxajVvQ1ZrOVdwQ3lGTDhtQkRrQVZVR2FVV3NRbEtPbzBvSlNlWUhzMUJGU0hZYjlweE5aMnZLS1FLVUtGZVB6" +
              "Mlk3ZnpNMnVPRmJiYUZZWXhCTGNOYmc0T0RldDd2MkJhbkVRYTd2c0xEUUVKZEUzbVFsMC9HbE04Z2tpaldSNkJFcm5hVGlJRFhKVm" +
              "cxaHBSR1hNcjdVVEVnWm9HUUtRT25TK1djV2p5WFBHWWExaE9POUZZemhnVmNuNE1FdXBCS3dVSXVSS3h5V2pGNkpwQzRHTEJva0hE" +
              "RHhDSTJlZHVncXpRK1BkWHluVVFnaUpueFA1eUo2dmg5K0w4N0x5K094cUI0alZ4Z3NlNHBGN1c2YkZRT1dqRTVpSWNSSkU5R2dRc3" +
              "VIRVE2UHhXemxwSWcxZC9MZXpvN2duWE5zdzhiRlQ1NmRQdjNpN05uejU3ZFRmNFhCNHFXRjJMQ3dZVFh4MHJJR1g2UWxGeUlFY1Fw" +
              "c3dTZ21KblIyclAzQmpqMTQrK2pSWSt2WEh3eUg1YTZjcmMwbWFSUkw4RU1Vckd5aXBxWGV6RUoxUVNTcytYQ0M2em5YY1NqeU1SSU" +
              "9pNzZ4aDVCbWlxV0dJbWpzSnQ1UXJHUVFNUXlQaGFzejRDVnQ4ZnhRWDNLeElWUEFzdlB6eVF1SG4yMVRsNnlGYUlxVThpMkV6SVFV" +
              "RzZtbXlVemFra094TEVKUHhESmo2ZXdtTXNFMnRlcXJnRmRqSVQrZHNpN01tVHNDckJveU1jMms2U1lCQjBBbDVsaVpLWVBZYWF4OH" +
              "BBem5uVWxJYmE3Qkpac0JZQ0xkTlZvN0lXNTZ2dUpmaVYzVENvS3lwZ0hLcElIaFhQT1pFV0pWRTE3dWRseW9PSXV2MXpWU3JGcVN5" +
              "bU1KV2dmb0xhbzJXVXJRQzRWV09RaEt0bFo1RldhREE2SXJ4bStudWxhRlFxOVlLQmhRYWpKWDZWbHFzSk5hVlZpa0tIaDVjTVVTUF" +
              "ZaS0crQ0xkTTRnSUJUN1RTWjAzYTlqeFJKK0p2UkdaaUwvTUlINmpWakFzRlJNMEJMbGk5alFyekRNMTNhK2huUS9KR1ZGb21HTS8r" +
              "WVBTU1BRdXJSL0VrdFpBQ3lNYWxTaitqMzZESlBYRlVmWVU0NDFBQUFBQUVsRlRrU3VRbUNDIiAvPjwvYT48L2Rpdj4=");
            document.body[atob("YXBwZW5kQ2hpbGQ=")](el.firstChild);
        })();
    });
})();
</script>
<style type="text/css">
    .is-mobile #viewBtn,
    .is-mobile #zoomBtn,
    .is-mobile #btnMove,
    .is-mobile #btnSelect,
    .is-mobile #btnZoomIn,
    .is-mobile #btnZoomOut {
        display: none;
    }

    #left {
        transition-timing-function: ease;
        transition-duration: 200ms;
        top: 45px;
        bottom: 0;
        position: absolute;
        overflow: hidden;
        z-index: 999;
        left: -350px;
        width: 350px;
    }
    .light-theme #left {
        border-right: 1px solid #7b8793;
    }
    .dark-theme #left {
        border-right: 1px solid #000;
    }
    #left.open {
        left: 0;
    }
    #left-controls {
        height: 44px;
        display: block;
    }
    #leftContent {
        top: 45px;
        bottom: 0;
        left: 0;
        right: 0;
        position: absolute;
        overflow-y: scroll;
        background-color: #eee;
        -webkit-overflow-scrolling: touch;
    }
    #btnOutlines {
        display: none;
    }
    #left.hasBookmarks #btnOutlines {
        display: inline;
    }
    #outlinePanel {
        display: none;
    }

    #pgCount {
        font-family: Arial,serif;
        vertical-align: middle;
        font-size: 15px;
    }
    #btnSelect, #btnZoomOut, #viewBtn {
        margin-left: 20px;
    }


    #goBtn, #zoomBtn, #viewBtn {
        height: 25px;
    }
    #goBtn {
        width: 55px;
    }
    #viewBtn {
        width: 105px;
    }
    #zoomBtn {
        width: 95px;
    }
    .thumbnail {
        cursor: pointer;
        display: block;
        padding: 8px 0;
        margin: 0 auto;
        text-align: center;
    }
    .thumbnail img{
        max-width: 160px;
        border-radius: 5px;
        border: 1px solid #bbb;
    }
    .currentPageThumbnail, .thumbnail:hover {
        background-color: #ddd;
    }
    .currentPageThumbnail img, .thumbnail:hover img {
        border: 1px solid #999;
    }

    #thumbnailPanel.visible, #outlinePanel.visible, #searchPanel.visible {
        display: inline;
    }
    #thumbnailPanel.hidden, #outlinePanel.hidden, #searchPanel.hidden {
        display: none;
    }
    #outlinePanel ul {
        list-style-type: none;
        padding: 0 5px;
    }
    #outlinePanel ul ul {
        padding-left: 15px;
        padding-right: 0;
    }
    #outlinePanel li {
        color: #333;
        padding: 2px;
        font-family: Arial,serif;
        font-size: 15px;
    }
    #outlinePanel li:hover {
        background-color: #ddd;
        cursor: pointer;
    }
    #searchPanel {
        font-family: Arial, sans-serif;
        font-size: 14px;
    }
    #searchPanel * {
        color: #333;
        margin: 5px;
    }
    #searchPanel #searchInput {
        color: black;
        border: 1px solid #666;
        width: 288px;
        display: block;
        padding: 5px;
        margin: 20px auto 10px;
    }
    #searchPanel .searchOption {
        margin: 0 20px;
        display: block;
    }
    #searchPanel hr {
        margin-top: 18px;
    }
    #searchPanel #searchResultsCount {
        text-align: center;
        display: block;
    }
    #searchPanel .result {
        text-decoration: none;
        display: block;
        word-wrap: break-word;
    }
    #searchPanel .result:hover {
        background-color: #ddd;
    }

    body {
        margin: 0;
        padding: 0;
    }

    .btn {
        border: 0 none;
        height: 30px;
        padding: 0;
        width: 30px;
        background-color: transparent;
        display: inline-block;
        margin: 7px 5px 0;
        vertical-align: top;
        cursor: pointer;
    }

    .page {
        box-shadow: 1px 1px 4px rgba(120, 120, 120, 0.5);
    }

    #controls {
        height: 44px;
        position: fixed;
        text-align: center;
        top: 0;
        left: 0;
        right: 0;
        transition: 0.3s ease 0s;
    }
    
    #controls select {
        margin-top: 10px;
    }
    
    #controls-left {
        display: inline-block;
        left: 0;
        position: absolute;
    }
    #controls-center {
        display: inline-block;
    }
    #controls-right {
        display: inline-block;
        right: 0;
        position: absolute;
    }

    .light-theme #idrviewer {
        background: #fafafa none repeat scroll 0 0;
    }
    .light-theme #controls,
    .light-theme #left-controls {
        background: #9eacba none repeat scroll 0 0;
        border-bottom: 1px solid #7b8793;
    }

    .light-theme #pgCount,
    .light-theme .btn {
        color: white;
        text-shadow: 0 0 1px #595959;
    }
    .light-theme .btn:hover {
        opacity: 0.6;
    }
    .light-theme .btn.disabled {
        opacity: 0.4;
    }

    .light-theme #goBtn,
    .light-theme #zoomBtn,
    .light-theme #viewBtn {
        background-color: #9aa8b6;
        color: white;
        border: 1px solid #7b8793;
    }

    .dark-theme #idrviewer {
        background: #666 none repeat scroll 0 0;
    }
    .dark-theme #controls,
    .dark-theme #left-controls {
        background: #444 none repeat scroll 0 0;
        border-bottom: 1px solid #000;
    }
    .dark-theme #pgCount {
        color: white;
        opacity: 0.8;
    }
    .dark-theme .btn {
        opacity: 0.7;
        color: white;
    }
    .dark-theme .btn:hover {
        opacity: 0.95;
    }
    .dark-theme .btn.disabled {
        opacity: 0.2;
    }

    .dark-theme #goBtn,
    .dark-theme #zoomBtn,
    .dark-theme #viewBtn {
        background-color: #656565;
        color: white;
        border: 1px solid #000;
    }

    #idrviewer {
        top: 45px;
        bottom: 0;
        left: 0;
        right: 0;
        position: absolute;
    }

    .spinner {
        border: 6px solid #bbb;
        border-top: 6px solid #3c9fe1;
        border-radius: 50%;
        width: 30px;
        height: 30px;
        margin: 0 auto;
    }

    .spinning {
        animation: spin 1s linear infinite;
    }

    @keyframes spin {
        0% { transform: rotate(0deg); }
        100% { transform: rotate(360deg); }
    }

</style>
</head>
<body class="light-theme">
    <nav id="left">
        <div id="left-controls">
            <button id="btnThumbnails" data-lang-title="control.thumbnails" title="Thumbnails" class="btn"><i class="fa fa-picture-o fa-lg" aria-hidden="true"></i></button>
            <button id="btnOutlines" data-lang-title="control.outlines" title="Bookmarks" class="btn"><i class="fa fa-list-ul fa-lg" aria-hidden="true"></i></button>
            <button id="btnSearch" data-lang-title="control.search" title="Search" class="btn"><i class="fa fa-search fa-lg" aria-hidden="true"></i></button>
        </div>
        <div id="leftContent">
            <div id="thumbnailPanel"></div>
            <div id="outlinePanel"></div>
            <div id="searchPanel">
                <input id="searchInput" data-lang-title="search.search" title="Search" type="text">
                <label class="searchOption"><input type="checkbox" id="cbMatchCase"><span data-lang-text="search.match-case"> Match case</span></label>
                <label class="searchOption"><input type="checkbox" id="cbLimitResults"><span data-lang-text="search.limit-results-1"> Limit results 1 per page</span></label>
                <hr>
                <span id="searchResultsCount"></span>
                <div id="searchResults"></div>
            </div>
        </div>
    </nav>

    <div id="main">
        <nav id="controls">
            <div id="controls-left">
                <button id="btnSideToggle" data-lang-title="control.sidebar" title="Sidebar" class="btn"><i class="fa fa-th fa-lg" aria-hidden="true"></i></button>
                <button id="btnThemeToggle" data-lang-title="control.theme-toggle" title="Theme Toggle" class="btn"><i class="fa fa-lightbulb-o fa-lg" aria-hidden="true"></i></button>
            </div>

            <div id="controls-center">
                <button id="btnPrev" data-lang-title="control.prev" title="Previous Page" class="btn"><i class="fa fa-caret-left fa-2x" aria-hidden="true"></i></button>
                <select id="goBtn">

                </select>
                <span id="pgCount"></span>
                <button id="btnNext" data-lang-title="control.next" title="Next Page" class="btn"><i class="fa fa-caret-right fa-2x" aria-hidden="true"></i></button>

                <button id="btnSelect" data-lang-title="control.select" title="Select" class="btn"><i class="fa fa-i-cursor fa-lg" aria-hidden="true"></i></button>
                <button id="btnMove" title="Pan" data-lang-title="control.move" class="btn"><i class="fa fa-arrows fa-lg" aria-hidden="true"></i></button>

                <button id="btnZoomOut" data-lang-title="control.zoom-out" title="Zoom Out" class="btn"><i class="fa fa-minus fa-lg" aria-hidden="true"></i></button>
                <select id="zoomBtn">
                    <option value="specific">100%</option>
                    <option data-lang-text="control.actual-size" value="actualsize">Actual Size</option>
                    <option data-lang-text="control.fit-width" value="fitwidth">Fit Width</option>
                    <option data-lang-text="control.fit-height" value="fitheight">Fit Height</option>
                    <option data-lang-text="control.fit-page" value="fitpage">Fit Page</option>
                    <option data-lang-text="control.auto" value="auto">Automatic</option>

                </select>
                <button id="btnZoomIn" data-lang-title="control.zoom-in" title="Zoom In" class="btn"><i class="fa fa-plus fa-lg" aria-hidden="true"></i></button>
            </div>
            <div id="controls-right">
                <button id="btnFullScreen" data-lang-title="control.fullscreen" title="Fullscreen" class="btn"><i class="fa fa-arrows-alt fa-lg" aria-hidden="true"></i></button>
            </div>
        </nav>

        <div id="idrviewer">

        </div>
    </div>
    <script src="config.js" type="text/javascript"></script>
    <script type="text/javascript">IDRViewer.setup();</script>
</body>
</html>

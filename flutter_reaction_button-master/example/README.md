# flutter_reaction_button_example

This is example Flutter Reaction Button Check:

<img src="https://github.com/GeekAbdelouahed/flutter-reaction-button/raw/master/images/Flutter-Reaction-Button-Check.gif"/>

```dart
FlutterReactionButtonCheck(
    onReactionChanged: (reaction, index, isChecked) {
        print('reaction selected index: $index');
    },
    reactions: <Reaction>[
        Reaction(
            previewIcon: buildWidgetPreview(
                icon: 'like.gif',
            ),
            icon: buildWidget(
                icon: 'like_fill.png'
            ),
        ),
        Reaction(
            previewIcon: buildWidgetPreview(
                icon: 'love.gif',
            ),
            icon: buildWidget(
                icon: 'love.png'
            ),
        ),
        Reaction(
            previewIcon: buildWidgetPreview(
                icon: 'wow.gif',
            ),
            icon: buildWidget(
                icon: 'wow.png'
            ),
        ),
        Reaction(
            previewIcon: buildWidgetPreview(
                icon: 'haha.gif',
            ),
            icon: buildWidget(
                icon: 'haha.png'
            ),
        ),
        Reaction(
            previewIcon: buildWidgetPreview(
                icon: 'sad.gif',
            ),
            icon: buildWidget(
                icon: 'sad.png'
            ),
        ),
        Reaction(
            previewIcon: buildWidgetPreview(
                icon: 'angry.gif',
            ),
            icon: buildWidget(
                icon: 'angry.png'
            ),
        ),
    ],
    initialReaction: Reaction(
        icon: buildWidget(
            icon: 'like.png'
        ),
    ),
    selectedReaction: Reaction(
        icon: buildWidget(
            icon: 'like_fill.png'
        ),
    ),
)
```



This is a example Flutter Reaction Button:

<img src="https://github.com/GeekAbdelouahed/flutter-reaction-button/raw/master/images/Flutter-Reaction-Button.gif"/>

```dart
FlutterReactionButton(
    onReactionChanged: (reaction, index) {
        print('reaction selected index: $index');
    },
    reactions: <Reaction>[
        Reaction(
            previewIcon: buildWidgetPreview(
                title: 'English',
                icon: 'united-kingdom-round.png',
            ),
            icon: buildWidget(
                icon: 'united-kingdom.png'
            ),
        ),
        Reaction(
            previewIcon: buildWidgetPreview(
                title: 'Arabic',
                icon: 'algeria-round.png',
            ),
            icon: buildWidget(
                icon: 'algeria.png'
            ),
        ),
        Reaction(
            previewIcon: buildWidgetPreview(
                title: 'German',
                icon: 'germany-round.png',
            ),
            icon: buildWidget(
                icon: 'germany.png'
            ),
        ),
        Reaction(
            previewIcon: buildWidgetPreview(
                title: 'Spanish',
                icon: 'spain-round.png',
            ),
            icon: buildWidget(
                icon: 'spain.png'
            ),
        ),
        Reaction(
            previewIcon: buildWidgetPreview(
                title: 'Chinese',
                icon: 'china-round.png',
            ),
            icon: buildWidget(
                icon: 'china.png'
            ),
        ),
    ],
    initialReaction: Reaction(
        previewIcon: buildWidgetPreview(
            title: 'English',
            icon: 'united-kingdom-round.png',
        ),
        icon: buildWidget(
            icon: 'united-kingdom.png'
        ),
    ),
)
```
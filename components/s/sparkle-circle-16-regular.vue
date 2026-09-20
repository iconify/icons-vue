<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dsl6v4btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sparkle-circle-16-regular" /></template>
<style>
.dsl6v4btg {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1m0 1a6 6 0 1 0 0 12A6 6 0 0 0 8 2m1.464 6.4c.16-.533.913-.533 1.072 0l.143.474a.67.67 0 0 0 .447.447l.475.143c.532.16.532.912 0 1.072l-.475.143a.67.67 0 0 0-.447.447l-.143.475c-.16.532-.912.532-1.072 0l-.144-.476a.67.67 0 0 0-.447-.447l-.474-.142c-.532-.16-.532-.912 0-1.072l.475-.143a.67.67 0 0 0 .446-.447zm-3.72-4.115c.252-.713 1.26-.713 1.512 0l.236.665a.92.92 0 0 0 .559.558l.665.236c.712.253.712 1.26 0 1.512l-.665.235a.92.92 0 0 0-.559.559l-.235.666c-.253.713-1.26.712-1.513-.001L5.51 8.05a.92.92 0 0 0-.559-.56l-.665-.235c-.713-.252-.713-1.26 0-1.512l.665-.236a.92.92 0 0 0 .559-.559z");
}

</style>

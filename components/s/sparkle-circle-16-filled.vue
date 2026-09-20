<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cqq42_h_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sparkle-circle-16-filled" /></template>
<style>
.cqq42_h_y {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1m2.536 7.4c-.16-.533-.912-.533-1.072 0l-.144.474a.67.67 0 0 1-.446.447l-.475.143c-.532.16-.532.913 0 1.072l.474.142a.67.67 0 0 1 .447.447l.144.476c.16.532.913.532 1.072 0l.143-.475a.67.67 0 0 1 .447-.447l.475-.143c.532-.16.532-.913 0-1.072l-.475-.143a.67.67 0 0 1-.447-.447zm-3.28-4.116c-.253-.712-1.26-.712-1.512.001l-.235.664a.92.92 0 0 1-.559.559l-.665.236c-.713.252-.713 1.26 0 1.512l.665.235a.92.92 0 0 1 .559.56l.235.664c.252.713 1.26.714 1.513 0l.235-.665a.92.92 0 0 1 .559-.559l.665-.235c.712-.253.712-1.26 0-1.512l-.665-.236a.92.92 0 0 1-.559-.558z");
}

</style>

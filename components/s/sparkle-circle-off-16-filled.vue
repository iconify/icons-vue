<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dkiq3xbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sparkle-circle-off-16-filled" /></template>
<style>
.dkiq3xbbx {
  fill: currentColor;
  d: path("M14.147 1.146a.5.5 0 1 1 .707.708l-1.565 1.563a7 7 0 0 1-9.872 9.872l-1.563 1.565a.5.5 0 1 1-.708-.707zM10.537 8.4c-.16-.532-.913-.532-1.073 0l-.144.475a.67.67 0 0 1-.446.447l-.475.143c-.532.16-.532.913 0 1.072l.474.142a.67.67 0 0 1 .447.447l.144.476c.16.532.913.532 1.072 0l.143-.475a.67.67 0 0 1 .447-.447l.475-.143c.532-.16.532-.913 0-1.072l-.475-.143a.67.67 0 0 1-.447-.447zM8 1c1.39 0 2.684.406 3.773 1.104L8.287 5.591l-.236-.083a.92.92 0 0 1-.559-.558l-.236-.666c-.253-.712-1.26-.712-1.512.001l-.235.664a.92.92 0 0 1-.559.559l-.665.236c-.713.252-.713 1.26 0 1.512l.665.235a.92.92 0 0 1 .559.56l.083.235l-3.488 3.487A7 7 0 0 1 8 1");
}

</style>

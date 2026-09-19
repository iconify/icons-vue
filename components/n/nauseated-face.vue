<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wb8qrvbam.css';
import '../../css/f/f5tq5acha.css';
import '../../css/s/s-v07-dkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="wb8qrvbam"/><path class="f5tq5acha"/><path class="s-v07-dkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:nauseated-face" /></template>

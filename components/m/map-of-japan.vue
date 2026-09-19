<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wldyddchs.css';
import '../../css/d/d1ny50d5n.css';
import '../../css/e/ediclqbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="wldyddchs"><path class="d1ny50d5n"/><path class="ediclqbms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:map-of-japan" /></template>

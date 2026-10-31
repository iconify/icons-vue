<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/c/cp7z90b6o.css';
import '../../css/f/f1u9n4bqt.css';
import '../../css/j/j1lwyvbxb.css';
import '../../css/f/f35-b8xpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="cp7z90b6o wm-shadow"/><path class="f1u9n4bqt wm-shadow"/><path class="j1lwyvbxb"/><path class="f35-b8xpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:rss" /></template>

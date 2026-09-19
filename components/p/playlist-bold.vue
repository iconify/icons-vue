<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3kb4cgpl.css';
import '../../css/a/ag8lg4baf.css';
import '../../css/w/wh6t2rs6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="r3kb4cgpl"><path class="ag8lg4baf"/><path class="wh6t2rs6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:playlist-bold" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um_si5o0k.css';
import '../../css/w/w755xk_8f.css';
import '../../css/n/nw4h7ac-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="um_si5o0k"><path class="w755xk_8f"/><path class="nw4h7ac-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:otne" /></template>

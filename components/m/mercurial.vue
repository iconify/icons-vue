<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_da3ubjp.css';
import '../../css/z/znrl4yb1y.css';
import '../../css/o/of9kz4-jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="r_da3ubjp"><path class="znrl4yb1y"/><path class="of9kz4-jf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:mercurial" /></template>

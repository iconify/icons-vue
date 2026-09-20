<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4t60vxkf.css';
import '../../css/d/do9x0cbvf.css';
import '../../css/j/j-15sc15t.css';
import '../../css/o/ofqb0_s4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="f4t60vxkf"/><path class="do9x0cbvf"/><path class="j-15sc15t"/><path class="ofqb0_s4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:strapi" /></template>

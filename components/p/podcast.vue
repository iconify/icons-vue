<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/z/zqktypdwy.css';
import '../../css/u/ufal36mvs.css';
import '../../css/k/k47fxrb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="wm-shadow zqktypdwy"/><path class="ufal36mvs wm-shadow"/><path class="k47fxrb9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:podcast" /></template>

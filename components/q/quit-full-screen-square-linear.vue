<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bc1hpiy2y.css';
import '../../css/k/krbrm1v9d.css';
import '../../css/e/e82515hbz.css';
import '../../css/u/u66s-fbqm.css';
import '../../css/x/xvjk-cbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bc1hpiy2y"/><path class="krbrm1v9d"/><path class="e82515hbz"/><path class="u66s-fbqm"/><path class="xvjk-cbox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:quit-full-screen-square-linear" /></template>

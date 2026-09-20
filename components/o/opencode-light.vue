<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti6n5-brp.css';
import '../../css/x/xlhg_tibn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g transform="matrix(1.5 0 0 1.5 -23.858 -7.25)"><path class="ti6n5-brp"/><rect class="xlhg_tibn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:opencode-light" /></template>

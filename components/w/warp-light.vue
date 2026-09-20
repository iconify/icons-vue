<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ed88bk2gg.css';
import '../../css/c/cnpgasf1a.css';
import '../../css/y/y7dn9kh7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ed88bk2gg"><path class="cnpgasf1a"/><path class="y7dn9kh7h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:warp-light" /></template>

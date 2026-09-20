<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a91r15bjt.css';
import '../../css/u/u50_rvyrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a91r15bjt"/><path class="u50_rvyrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:twine" /></template>

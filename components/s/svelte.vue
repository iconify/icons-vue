<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkjo3ifcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":300};
const content = `<path class="wkjo3ifcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:svelte" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryq49vj0z.css';
import '../../css/i/iz9ll_bww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ryq49vj0z"/><path class="iz9ll_bww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:url" /></template>

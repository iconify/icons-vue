<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zo7g7xbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zo7g7xbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:screen-full" /></template>

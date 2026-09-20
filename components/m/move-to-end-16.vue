<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yonlo3bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yonlo3bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:move-to-end-16" /></template>

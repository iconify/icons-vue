<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv5b60b3j.css';
import '../../css/z/z8r7eipgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lv5b60b3j"/><path class="z8r7eipgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:typescript" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0xwpgbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="x0xwpgbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:swagger" /></template>

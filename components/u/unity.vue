<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emundtb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="emundtb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:unity" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udrja85vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="udrja85vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:medal-2nd" /></template>

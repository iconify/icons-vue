<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4b1xmw_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j4b1xmw_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:no-symbol" /></template>

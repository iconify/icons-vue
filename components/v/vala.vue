<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u59a1m3qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u59a1m3qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:vala" /></template>

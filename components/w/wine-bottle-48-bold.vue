<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw-mwgb5w.css';
import '../../css/w/wt36fcmmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jw-mwgb5w"/><path class="wt36fcmmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wine-bottle-48-bold" /></template>

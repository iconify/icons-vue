<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo3ndbcqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="bo3ndbcqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:uiwindow-split-2x1" /></template>

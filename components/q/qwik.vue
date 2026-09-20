<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of9o9pahi.css';
import '../../css/r/rq1sw1bve.css';
import '../../css/d/dfa3o1blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="of9o9pahi"/><path class="rq1sw1bve"/><path class="dfa3o1blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:qwik" /></template>

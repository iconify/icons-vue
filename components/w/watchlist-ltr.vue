<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0hy8ybjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q0hy8ybjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:watchlist-ltr" /></template>

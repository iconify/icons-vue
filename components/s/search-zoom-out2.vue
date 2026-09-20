<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xojf1ebkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xojf1ebkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:search-zoom-out2" /></template>

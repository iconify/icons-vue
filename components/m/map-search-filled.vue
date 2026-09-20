<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3jy0q-gs.css';
import '../../css/w/w_-a5y10p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3jy0q-gs"/><path class="w_-a5y10p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-search-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i99h-_v1d.css';
import '../../css/x/xspkd8upa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i99h-_v1d"/><path class="xspkd8upa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:medal" /></template>

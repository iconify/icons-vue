<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xar2vs8av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xar2vs8av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:point-out" /></template>

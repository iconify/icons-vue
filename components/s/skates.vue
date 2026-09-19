<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jzo2gzbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jzo2gzbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:skates" /></template>

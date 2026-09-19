<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgv7xwfjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dgv7xwfjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:waterfalls-v" /></template>

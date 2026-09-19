<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy_70-b1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yy_70-b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:palace" /></template>

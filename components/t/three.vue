<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3h087bjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p3h087bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:three" /></template>

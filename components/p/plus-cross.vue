<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkfa51bsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qkfa51bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:plus-cross" /></template>

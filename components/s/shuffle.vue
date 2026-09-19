<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl9h3zbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zl9h3zbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:shuffle" /></template>

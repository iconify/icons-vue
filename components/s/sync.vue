<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqyji8tcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jqyji8tcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sync" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojwjjvbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ojwjjvbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:point" /></template>

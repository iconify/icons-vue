<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xha8meb5n.css';
import '../../css/o/owtzvwbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xha8meb5n"/><path class="owtzvwbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:plane-private" /></template>

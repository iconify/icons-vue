<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0kv021sy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0kv021sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:map-pins-plus" /></template>

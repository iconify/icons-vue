<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt0fh2bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt0fh2bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sale-circle" /></template>

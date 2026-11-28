<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo0x7ob7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bo0x7ob7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:text-overflow" /></template>

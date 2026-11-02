<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7zzxx1cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7zzxx1cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tree-4-fill" /></template>

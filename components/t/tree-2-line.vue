<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrsecjgnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrsecjgnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tree-2-line" /></template>

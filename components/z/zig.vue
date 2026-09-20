<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhe8t8ahy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":176};
const content = `<path class="xhe8t8ahy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zig" /></template>

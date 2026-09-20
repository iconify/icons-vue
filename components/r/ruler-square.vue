<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq9fdxb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zq9fdxb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:ruler-square" /></template>

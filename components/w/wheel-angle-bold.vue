<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkv2srbts.css';
import '../../css/g/g47xhxbse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkv2srbts"/><path clip-rule="evenodd" class="g47xhxbse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wheel-angle-bold" /></template>

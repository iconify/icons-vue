<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmu0x6ayu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmu0x6ayu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sonic" /></template>

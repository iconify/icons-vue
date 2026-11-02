<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl7idjs2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pl7idjs2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:typography-line" /></template>

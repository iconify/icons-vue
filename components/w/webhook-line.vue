<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8w2j4bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8w2j4bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:webhook-line" /></template>

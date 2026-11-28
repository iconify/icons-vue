<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkv6zgbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkv6zgbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:square-6" /></template>

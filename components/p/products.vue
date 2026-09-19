<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i69c5cblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i69c5cblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:products" /></template>

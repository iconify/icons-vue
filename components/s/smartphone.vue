<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-6a3v2fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-6a3v2fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone" /></template>

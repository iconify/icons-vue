<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct1q-zx5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct1q-zx5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:social-x-line" /></template>

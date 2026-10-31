<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx0oicvhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx0oicvhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-chevron-double-up-round" /></template>

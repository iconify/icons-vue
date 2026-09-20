<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfio52e4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cfio52e4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pnpm" /></template>

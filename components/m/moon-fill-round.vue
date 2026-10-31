<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chwt8zbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chwt8zbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:moon-fill-round" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh6ermwwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh6ermwwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:uv-01" /></template>

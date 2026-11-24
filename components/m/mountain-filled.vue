<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba8-88ads.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba8-88ads"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mountain-filled" /></template>

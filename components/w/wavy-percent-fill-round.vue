<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl39cw6wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl39cw6wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-percent-fill-round" /></template>

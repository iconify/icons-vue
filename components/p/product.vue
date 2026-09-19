<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjc7jhbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjc7jhbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:product" /></template>

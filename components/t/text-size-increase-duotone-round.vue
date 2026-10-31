<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vx364u-2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vx364u-2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-size-increase-duotone-round" /></template>

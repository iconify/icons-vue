<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sek5qrbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sek5qrbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-6-duotone-round" /></template>

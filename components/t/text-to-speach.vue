<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcrnawbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gcrnawbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-to-speach" /></template>

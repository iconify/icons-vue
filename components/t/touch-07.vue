<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk279t5iv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk279t5iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:touch-07" /></template>

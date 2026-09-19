<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di6q9o7nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di6q9o7nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:zoom-out" /></template>

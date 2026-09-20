<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6w8ogbfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6w8ogbfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:netflix-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypb-jhynf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypb-jhynf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ship-2-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy_9tw95l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy_9tw95l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:vuejs-line" /></template>

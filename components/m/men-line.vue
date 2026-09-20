<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn728lqcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn728lqcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:men-line" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy_b46cyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy_b46cyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:option-sharp-duotone" /></template>

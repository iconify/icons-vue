<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxjoesbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxjoesbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:truck-plus" /></template>

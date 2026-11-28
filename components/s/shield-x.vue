<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k68w13ofn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k68w13ofn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:shield-x" /></template>

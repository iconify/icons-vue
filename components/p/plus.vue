<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-nz76glx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-nz76glx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:plus" /></template>

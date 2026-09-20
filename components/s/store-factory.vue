<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2r0f0b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2r0f0b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:store-factory" /></template>

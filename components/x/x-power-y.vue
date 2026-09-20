<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frtsr5bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frtsr5bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:x-power-y" /></template>

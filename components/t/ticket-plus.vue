<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep8a0-bfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep8a0-bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:ticket-plus" /></template>

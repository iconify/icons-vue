<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4t08bbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x4t08bbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:percentage" /></template>

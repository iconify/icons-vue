<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cet4g5u_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cet4g5u_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:milkshake" /></template>

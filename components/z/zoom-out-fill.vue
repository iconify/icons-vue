<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw8x8r-ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw8x8r-ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:zoom-out-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1pb_cbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1pb_cbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safe-flash-line" /></template>

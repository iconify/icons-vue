<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr3rkb2_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rr3rkb2_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-dashed-mouse-pointer" /></template>

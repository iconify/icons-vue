<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir_jl2baq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ir_jl2baq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:potted-flower-tulip-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl_1o55vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl_1o55vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:settings-6-line" /></template>

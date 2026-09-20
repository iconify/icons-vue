<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx7nh0b0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="tx7nh0b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:mountain-11" /></template>

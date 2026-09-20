<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc7-71b7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc7-71b7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:sad-squint" /></template>

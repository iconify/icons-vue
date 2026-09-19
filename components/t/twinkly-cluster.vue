<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5y0of55f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5y0of55f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:twinkly-cluster" /></template>

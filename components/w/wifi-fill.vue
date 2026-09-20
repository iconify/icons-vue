<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l06t19rlj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l06t19rlj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wifi-fill" /></template>

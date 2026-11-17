<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6bt5fbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6bt5fbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:trafficdotcv" /></template>

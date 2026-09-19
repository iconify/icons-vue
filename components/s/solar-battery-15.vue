<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afustmhrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afustmhrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:solar-battery-15" /></template>

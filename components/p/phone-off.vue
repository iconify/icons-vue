<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsaaqfdod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsaaqfdod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:phone-off" /></template>

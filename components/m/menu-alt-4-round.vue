<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmoe46bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmoe46bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-alt-4-round" /></template>

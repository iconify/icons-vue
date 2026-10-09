<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_vc3bc-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q_vc3bc-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:star-half-20" /></template>

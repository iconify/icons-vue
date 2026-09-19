<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_mzs6bfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="q_mzs6bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:translate-hangul-latin" /></template>

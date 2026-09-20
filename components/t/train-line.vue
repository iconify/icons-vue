<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1q90pr3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1q90pr3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:train-line" /></template>

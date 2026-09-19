<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otpvh6y5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="shield-outline"><path class="(Stroke) 69 Vector otpvh6y5u" clip-rule="evenodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:shield-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvt1tccbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvt1tccbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:psychotherapy-line" /></template>

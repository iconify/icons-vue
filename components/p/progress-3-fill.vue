<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcz2uwtww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcz2uwtww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:progress-3-fill" /></template>

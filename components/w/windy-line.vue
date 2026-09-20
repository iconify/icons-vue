<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfnsi60mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfnsi60mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:windy-line" /></template>

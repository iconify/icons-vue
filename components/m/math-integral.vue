<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf_9sb64s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf_9sb64s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:math-integral" /></template>

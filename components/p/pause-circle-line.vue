<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqk-xh9az.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqk-xh9az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pause-circle-line" /></template>

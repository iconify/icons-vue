<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njpbjcc-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njpbjcc-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mini-program-line" /></template>

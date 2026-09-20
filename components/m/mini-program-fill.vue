<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwniernpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kwniernpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mini-program-fill" /></template>

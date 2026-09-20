<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g432uxb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g432uxb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:play-list-fill" /></template>

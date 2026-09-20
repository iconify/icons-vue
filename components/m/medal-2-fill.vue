<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0fuz5boh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0fuz5boh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:medal-2-fill" /></template>

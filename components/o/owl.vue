<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goq3nlbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="goq3nlbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:owl" /></template>

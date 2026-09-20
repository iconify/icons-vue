<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgi-stgjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgi-stgjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:takeoff-fill" /></template>

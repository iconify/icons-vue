<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_s5z_bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="u_s5z_bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:plug-circle-check" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd4_m4bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gd4_m4bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:phone" /></template>

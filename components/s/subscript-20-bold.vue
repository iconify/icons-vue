<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy3-jm4dn.css';
import '../../css/h/h0d_lm9zw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iy3-jm4dn"/><path class="h0d_lm9zw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:subscript-20-bold" /></template>

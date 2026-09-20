<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu3x4jbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qu3x4jbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:utensil-spoon" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1qjmetax.css';
import '../../css/e/ev3t13bln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v1qjmetax"/><path class="ev3t13bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:newspaper-20" /></template>

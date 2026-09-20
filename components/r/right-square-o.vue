<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwmoskb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fwmoskb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:right-square-o" /></template>

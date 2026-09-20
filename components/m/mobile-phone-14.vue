<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkwb1-b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="tkwb1-b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:mobile-phone-14" /></template>

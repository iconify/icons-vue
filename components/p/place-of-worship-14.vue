<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oixz44knh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="oixz44knh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:place-of-worship-14" /></template>

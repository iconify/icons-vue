<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofyn4sb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ofyn4sb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:phone-circle-fill" /></template>

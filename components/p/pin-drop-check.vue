<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0p6_fbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0p6_fbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:pin-drop-check" /></template>

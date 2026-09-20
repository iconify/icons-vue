<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt_88-bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt_88-bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:xda-developers" /></template>

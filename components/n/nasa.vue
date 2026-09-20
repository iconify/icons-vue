<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp30hdueg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kp30hdueg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:nasa" /></template>

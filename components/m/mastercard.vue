<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpywcvzzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpywcvzzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:mastercard" /></template>

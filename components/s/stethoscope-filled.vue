<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lterprbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lterprbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:stethoscope-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpkk2ibpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpkk2ibpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:map-pin-5-fill" /></template>

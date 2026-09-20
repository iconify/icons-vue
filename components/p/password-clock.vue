<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcgh8u5lz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcgh8u5lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:password-clock" /></template>

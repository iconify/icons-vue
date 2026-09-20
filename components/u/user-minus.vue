<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntffnhbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntffnhbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:user-minus" /></template>

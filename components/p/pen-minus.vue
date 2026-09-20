<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mojktesdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mojktesdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pen-minus" /></template>

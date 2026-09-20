<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3jz38zow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3jz38zow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:network-cash-box" /></template>

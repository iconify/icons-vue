<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oosyq6bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oosyq6bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-strength-2-alert" /></template>

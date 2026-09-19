<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8z775b8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8z775b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:smartphone-nfc" /></template>

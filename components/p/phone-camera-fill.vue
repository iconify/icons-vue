<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6s5vmn0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6s5vmn0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:phone-camera-fill" /></template>

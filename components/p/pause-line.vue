<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe3j4133w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oe3j4133w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pause-line" /></template>

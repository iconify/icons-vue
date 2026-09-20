<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5omk_79g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5omk_79g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pin-distance-line" /></template>

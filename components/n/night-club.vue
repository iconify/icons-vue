<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0k6s5bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="c0k6s5bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:night-club" /></template>

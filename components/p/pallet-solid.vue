<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg55910fy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tg55910fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:pallet-solid" /></template>

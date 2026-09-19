<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2sotnbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i2sotnbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:rainy-sharp" /></template>

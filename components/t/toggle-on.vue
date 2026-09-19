<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdc_jgbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="bdc_jgbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:toggle-on" /></template>

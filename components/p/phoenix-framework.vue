<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah-h2x4ww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ah-h2x4ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:phoenix-framework" /></template>

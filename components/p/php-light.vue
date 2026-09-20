<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj2vy9b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":50,"top":-1};
const content = `<path class="zj2vy9b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:php-light" /></template>

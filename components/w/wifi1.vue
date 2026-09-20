<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxxhy_bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mxxhy_bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:wifi1" /></template>

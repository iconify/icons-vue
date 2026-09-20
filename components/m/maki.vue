<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj0x7hbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fj0x7hbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:maki" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1h5u9bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="u1h5u9bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:trash-can-arrow-up" /></template>

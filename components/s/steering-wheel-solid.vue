<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2vltv_6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r2vltv_6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:steering-wheel-solid" /></template>

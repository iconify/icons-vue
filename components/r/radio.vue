<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4bv7_8rk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u4bv7_8rk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:radio" /></template>

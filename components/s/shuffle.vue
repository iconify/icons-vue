<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0b0racfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k0b0racfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:shuffle" /></template>

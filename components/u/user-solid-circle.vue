<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgtnslbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vgtnslbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:user-solid-circle" /></template>

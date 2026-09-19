<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-yyo-b_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="j-yyo-b_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:map-pin-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv2_p-9yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="mv2_p-9yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:stumbleupon-circle" /></template>

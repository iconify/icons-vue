<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laa4fbevb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="laa4fbevb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:page4" /></template>

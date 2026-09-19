<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/img8e6bfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="img8e6bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:palfed" /></template>

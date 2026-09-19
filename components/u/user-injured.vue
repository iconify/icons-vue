<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vix_qxzzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="vix_qxzzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user-injured" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm71xnlzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sm71xnlzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:pen-square-solid" /></template>

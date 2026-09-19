<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/my8c60b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="my8c60b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:plangrid" /></template>

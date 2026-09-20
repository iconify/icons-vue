<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/so_azubcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="so_azubcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:plus-circle-solid" /></template>

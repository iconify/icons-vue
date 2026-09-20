<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk3v_nvcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vk3v_nvcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:storj-dark" /></template>

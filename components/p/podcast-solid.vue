<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_3-1wabe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i_3-1wabe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:podcast-solid" /></template>

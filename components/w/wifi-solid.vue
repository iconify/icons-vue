<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0ake8x4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0ake8x4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:wifi-solid" /></template>

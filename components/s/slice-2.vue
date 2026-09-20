<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfortsbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="gfortsbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:slice-2" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz4tflwpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="wz4tflwpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:radiation-alt" /></template>

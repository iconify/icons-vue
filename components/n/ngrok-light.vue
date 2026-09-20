<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wct01yjnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":200,"height":92.11};
const content = `<path class="wct01yjnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ngrok-light" /></template>

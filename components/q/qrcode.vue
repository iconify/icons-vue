<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_a55lb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1408};
const content = `<path class="z_a55lb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:qrcode" /></template>

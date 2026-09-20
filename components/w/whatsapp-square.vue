<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohn5t9b4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ohn5t9b4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:whatsapp-square" /></template>

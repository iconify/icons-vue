<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vat3ri6pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="vat3ri6pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:note-sticky" /></template>

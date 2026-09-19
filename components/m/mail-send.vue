<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uibprsbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":384};
const content = `<path class="uibprsbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:mail-send" /></template>

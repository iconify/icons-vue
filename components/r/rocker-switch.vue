<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f23c3tblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f23c3tblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rocker-switch" /></template>

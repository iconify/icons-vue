<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m46032bav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m46032bav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sun-medium-solid" /></template>

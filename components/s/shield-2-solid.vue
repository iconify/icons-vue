<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g72s21blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g72s21blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:shield-2-solid" /></template>

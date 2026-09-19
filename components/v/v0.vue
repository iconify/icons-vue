<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn38t4bmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bn38t4bmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:v0" /></template>

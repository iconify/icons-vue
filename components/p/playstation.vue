<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsyxn_5xa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="vsyxn_5xa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:playstation" /></template>

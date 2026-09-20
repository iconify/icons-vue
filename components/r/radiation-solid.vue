<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pweqiyblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pweqiyblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:radiation-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz_qnk-ze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1786,"height":428,"left":107,"top":786};
const content = `<path class="kz_qnk-ze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tata-consultancy-services-light" /></template>

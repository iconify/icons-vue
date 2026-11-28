<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg_p-hb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1786,"height":428,"left":107,"top":786};
const content = `<path class="wg_p-hb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tata-consultancy-services-dark" /></template>

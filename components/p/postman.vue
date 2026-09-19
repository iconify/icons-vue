<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5pe20bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m5pe20bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:postman" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt-xabb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zt-xabb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:procedures-solid" /></template>

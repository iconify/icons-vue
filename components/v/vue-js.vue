<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky387gxav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ky387gxav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:vue-js" /></template>

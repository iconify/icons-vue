<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpx8s0bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lpx8s0bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:upload-solid" /></template>

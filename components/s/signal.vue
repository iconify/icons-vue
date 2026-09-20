<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7642b9dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="m7642b9dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:signal" /></template>

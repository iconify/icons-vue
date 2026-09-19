<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8urf5jax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o8urf5jax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:nominal" /></template>

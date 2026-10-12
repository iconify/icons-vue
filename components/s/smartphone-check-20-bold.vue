<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/veoutmb5y.css';
import '../../css/n/nutvqx2bw.css';
import '../../css/s/sh06c0bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="veoutmb5y"/><path class="nutvqx2bw"/><path class="sh06c0bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smartphone-check-20-bold" /></template>

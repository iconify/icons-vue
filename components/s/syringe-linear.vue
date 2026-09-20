<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lllc-r1nz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lllc-r1nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:syringe-linear" /></template>

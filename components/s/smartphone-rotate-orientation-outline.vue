<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmit9yp1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cmit9yp1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smartphone-rotate-orientation-outline" /></template>

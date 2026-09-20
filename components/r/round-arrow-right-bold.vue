<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0p2vxb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c0p2vxb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-arrow-right-bold" /></template>

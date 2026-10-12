<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2scobdvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2scobdvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:skip-back-filled" /></template>

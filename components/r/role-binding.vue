<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzkun1bgf.css';
import '../../css/m/m5u32yv6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzkun1bgf"/><path class="m5u32yv6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:role-binding" /></template>

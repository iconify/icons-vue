<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcu23r-dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcu23r-dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sim-card-2-line" /></template>

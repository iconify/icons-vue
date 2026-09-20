<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_nxf9b7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_nxf9b7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shield-star-fill" /></template>

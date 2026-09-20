<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_jjm0b1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_jjm0b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:meta-fill" /></template>

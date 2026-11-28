<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khpwbvb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khpwbvb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shield-heart-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m__3b_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m__3b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:purse" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da_olsb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da_olsb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pencil-fill" /></template>

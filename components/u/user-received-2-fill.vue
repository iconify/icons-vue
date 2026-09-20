<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es3k_-b0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="es3k_-b0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:user-received-2-fill" /></template>

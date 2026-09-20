<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo_h-m8ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo_h-m8ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-security-fill" /></template>

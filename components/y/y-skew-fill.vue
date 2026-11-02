<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8n0gbwvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8n0gbwvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:y-skew-fill" /></template>

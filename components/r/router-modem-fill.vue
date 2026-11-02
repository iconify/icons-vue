<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3t8upb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3t8upb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:router-modem-fill" /></template>

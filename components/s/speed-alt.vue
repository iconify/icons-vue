<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqxl8rbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sqxl8rbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:speed-alt" /></template>

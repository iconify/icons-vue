<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_uv_mx1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n_uv_mx1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:money" /></template>

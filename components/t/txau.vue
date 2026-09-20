<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_8xi44zz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g_8xi44zz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:txau" /></template>

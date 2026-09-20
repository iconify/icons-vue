<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcawit-zx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcawit-zx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:sudo" /></template>

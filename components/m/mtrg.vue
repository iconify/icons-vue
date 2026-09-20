<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx2t3vb9s.css';
import '../../css/q/qr0d49tfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx2t3vb9s"/><path class="qr0d49tfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:mtrg" /></template>

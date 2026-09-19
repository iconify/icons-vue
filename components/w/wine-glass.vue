<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtdvku_qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtdvku_qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:wine-glass" /></template>

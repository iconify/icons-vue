<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhynbvk_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mhynbvk_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nav" /></template>

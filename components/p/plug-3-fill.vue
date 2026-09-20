<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufpbpac8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufpbpac8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:plug-3-fill" /></template>

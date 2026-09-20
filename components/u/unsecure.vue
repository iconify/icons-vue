<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8p61p_5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t8p61p_5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:unsecure" /></template>

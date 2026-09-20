<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj2goybcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj2goybcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:medium-quality" /></template>

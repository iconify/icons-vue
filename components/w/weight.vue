<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg_6hwbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg_6hwbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:weight" /></template>

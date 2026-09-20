<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cagmclbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cagmclbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:save-3-fill" /></template>

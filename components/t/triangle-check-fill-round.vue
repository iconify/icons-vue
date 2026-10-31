<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0895sbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0895sbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-check-fill-round" /></template>

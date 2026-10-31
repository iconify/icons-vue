<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzjrplyuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzjrplyuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-up-round" /></template>

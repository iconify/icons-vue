<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzj3hwbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzj3hwbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:trash" /></template>

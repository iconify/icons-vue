<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsfp_ybjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsfp_ybjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-cog" /></template>

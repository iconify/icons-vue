<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug2zzqy7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug2zzqy7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:parenthesis-left" /></template>

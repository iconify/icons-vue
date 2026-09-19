<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym3v0_fpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym3v0_fpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:trx" /></template>

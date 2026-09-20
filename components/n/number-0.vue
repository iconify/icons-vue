<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbsqw0x7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbsqw0x7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-0" /></template>

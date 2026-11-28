<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqu3ykbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqu3ykbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:number-3-solid" /></template>

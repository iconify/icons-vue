<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdpu8s45u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdpu8s45u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mat-line" /></template>

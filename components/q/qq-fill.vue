<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzru7zzlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nzru7zzlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:qq-fill" /></template>

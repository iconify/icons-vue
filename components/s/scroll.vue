<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nss4h2bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nss4h2bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:scroll" /></template>

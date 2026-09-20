<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm2gtmtka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gm2gtmtka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:summit-remix" /></template>

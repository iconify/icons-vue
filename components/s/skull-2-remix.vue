<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rptmc5brg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rptmc5brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:skull-2-remix" /></template>

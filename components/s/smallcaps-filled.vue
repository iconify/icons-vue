<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rab3i_pim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rab3i_pim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:smallcaps-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyt6z2bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyt6z2bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-letter-l-filled" /></template>

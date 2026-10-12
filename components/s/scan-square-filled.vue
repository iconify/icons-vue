<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_tbmpogi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_tbmpogi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:scan-square-filled" /></template>

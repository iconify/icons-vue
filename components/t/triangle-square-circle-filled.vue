<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8k_0xmwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8k_0xmwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:triangle-square-circle-filled" /></template>

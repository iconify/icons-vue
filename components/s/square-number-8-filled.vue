<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f69z4_btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f69z4_btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-number-8-filled" /></template>

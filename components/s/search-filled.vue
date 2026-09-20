<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8fsovboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8fsovboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:search-filled" /></template>

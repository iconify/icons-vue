<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy_ywwbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy_ywwbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-column-plus-after" /></template>

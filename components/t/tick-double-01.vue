<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoo_40b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xoo_40b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tick-double-01" /></template>

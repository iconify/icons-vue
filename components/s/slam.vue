<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxq4srb0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxq4srb0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:slam" /></template>

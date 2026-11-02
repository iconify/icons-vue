<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trsk72z_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trsk72z_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:swimming-pool-fill" /></template>

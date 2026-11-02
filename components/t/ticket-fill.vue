<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r888i_z2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r888i_z2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ticket-fill" /></template>

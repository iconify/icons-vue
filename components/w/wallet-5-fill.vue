<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-l1nhb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-l1nhb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wallet-5-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si2_iqbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si2_iqbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:no-credit-card" /></template>

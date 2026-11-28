<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgs59abro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgs59abro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:triangle-dashed-solid" /></template>

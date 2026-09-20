<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfb0ibcol.css';
import '../../css/m/m1m99qwsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lfb0ibcol"/><path class="m1m99qwsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:money-protection" /></template>

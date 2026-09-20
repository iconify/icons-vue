<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txjhcum_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="txjhcum_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:paramount-plus-dark" /></template>

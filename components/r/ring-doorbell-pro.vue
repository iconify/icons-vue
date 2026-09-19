<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r58i4harq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r58i4harq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ring-doorbell-pro" /></template>

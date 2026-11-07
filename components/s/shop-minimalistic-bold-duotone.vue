<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl7l5cbrw.css';
import '../../css/n/nur9zm4bq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl7l5cbrw"/><path class="nur9zm4bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shop-minimalistic-bold-duotone" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpv6dt-5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpv6dt-5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:stats-up-alt" /></template>

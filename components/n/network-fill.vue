<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_5nsrb-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_5nsrb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:network-fill" /></template>

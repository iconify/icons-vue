<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke7pn4bgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke7pn4bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:no-credit-card-line" /></template>

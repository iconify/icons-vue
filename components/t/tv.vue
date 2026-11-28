<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5pkw1bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5pkw1bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tv" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtxs9fivs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtxs9fivs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-minimalistic-bold" /></template>

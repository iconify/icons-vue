<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5yhmcb_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="w5yhmcb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:shield" /></template>

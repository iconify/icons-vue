<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij0_li78p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ij0_li78p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:target" /></template>

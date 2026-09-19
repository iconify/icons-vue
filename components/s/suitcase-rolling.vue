<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0u-p9smw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="t0u-p9smw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:suitcase-rolling" /></template>

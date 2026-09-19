<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlxe_2blb.css';
import '../../css/t/tum5xlert.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlxe_2blb"/><path class="tum5xlert"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:print-dollar" /></template>

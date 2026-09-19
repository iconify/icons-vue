<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6_7uibvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6_7uibvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:zoom-out" /></template>

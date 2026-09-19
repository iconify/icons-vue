<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e59x_pbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e59x_pbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:yaki-dango" /></template>

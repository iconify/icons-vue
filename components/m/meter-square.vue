<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnha55g-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnha55g-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:meter-square" /></template>

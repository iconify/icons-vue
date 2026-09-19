<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbtm1819t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbtm1819t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rows" /></template>

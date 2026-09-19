<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er3yn_rep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er3yn_rep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:saudi-riyal" /></template>

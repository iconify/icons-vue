<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpuw_nboq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpuw_nboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:windsock" /></template>

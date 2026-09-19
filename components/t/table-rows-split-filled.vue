<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocsa8ub0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocsa8ub0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:table-rows-split-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st-ub119n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st-ub119n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:sapling-filled" /></template>

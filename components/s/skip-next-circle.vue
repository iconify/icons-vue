<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkyoe0byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkyoe0byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:skip-next-circle" /></template>

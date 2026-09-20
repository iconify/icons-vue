<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_1g5tbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o_1g5tbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:solectrus" /></template>

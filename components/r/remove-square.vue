<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drmj1obvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drmj1obvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:remove-square" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izyqqwbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izyqqwbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:table-properties" /></template>

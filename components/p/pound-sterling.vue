<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfxbc5b_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yfxbc5b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pound-sterling" /></template>

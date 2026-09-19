<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn13i-b0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn13i-b0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:table-columns-split" /></template>

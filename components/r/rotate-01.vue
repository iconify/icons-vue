<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn9vvrb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mn9vvrb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rotate-01" /></template>

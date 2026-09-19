<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1n2isbof.css';
import '../../css/m/mn36lt97b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1n2isbof"/><path class="mn36lt97b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:self-care" /></template>

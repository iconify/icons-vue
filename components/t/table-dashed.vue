<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwy8jabsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwy8jabsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:table-dashed" /></template>

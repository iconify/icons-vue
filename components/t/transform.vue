<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6n17x5tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6n17x5tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:transform" /></template>

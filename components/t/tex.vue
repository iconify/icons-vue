<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tow6czris.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tow6czris"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:tex" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtus7tvkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtus7tvkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-cells-split-round" /></template>

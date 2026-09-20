<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5intkb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5intkb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:solar-panel-2" /></template>

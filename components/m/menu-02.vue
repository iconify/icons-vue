<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdmn220di.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdmn220di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:menu-02" /></template>

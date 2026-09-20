<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb3m0hb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="tb3m0hb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:tooltip-end-help" /></template>

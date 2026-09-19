<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itafvib0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="itafvib0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:move" /></template>

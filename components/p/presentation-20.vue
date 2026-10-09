<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pze-k_dmv.css';
import '../../css/a/ad5vgcley.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pze-k_dmv"/><path class="ad5vgcley"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:presentation-20" /></template>

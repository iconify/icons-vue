<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rixbikb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rixbikb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:peak-shaving-20" /></template>

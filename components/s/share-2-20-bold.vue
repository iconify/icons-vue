<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs4tj7b-n.css';
import '../../css/r/rn3p8rbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hs4tj7b-n"/><path class="rn3p8rbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:share-2-20-bold" /></template>

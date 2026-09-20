<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2so9dl7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="p2so9dl7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:media-stop" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncbe981cb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ncbe981cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:map-pin-slash-thin" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc2v17baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sc2v17baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:play" /></template>

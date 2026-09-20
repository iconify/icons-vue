<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5g7d5bvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="w5g7d5bvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:shuffleboard" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srefg3b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="srefg3b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wide-p-in-parking-structure" /></template>

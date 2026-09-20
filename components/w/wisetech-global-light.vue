<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rspr33bfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1534,"height":1534};
const content = `<path class="rspr33bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:wisetech-global-light" /></template>

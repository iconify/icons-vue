<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wti_j-baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":40};
const content = `<path class="wti_j-baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:patreon-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2uz6p22g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c2uz6p22g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:pdiddy" /></template>

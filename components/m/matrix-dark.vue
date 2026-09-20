<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf81h_pns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="wf81h_pns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:matrix-dark" /></template>

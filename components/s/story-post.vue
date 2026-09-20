<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kigtyvbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="kigtyvbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:story-post" /></template>

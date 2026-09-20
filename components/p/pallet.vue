<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v82j94bfo.css';
import '../../css/d/dgp4q7bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="v82j94bfo"/><path class="dgp4q7bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pallet" /></template>

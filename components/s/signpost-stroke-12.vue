<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szy1_ul7k.css';
import '../../css/f/fgrg7ftet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="szy1_ul7k"/><path class="fgrg7ftet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:signpost-stroke-12" /></template>

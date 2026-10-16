<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1vduib2t.css';
import '../../css/h/htcxxr-ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n1vduib2t"/><path class="htcxxr-ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:warming-stripes-20-bold" /></template>

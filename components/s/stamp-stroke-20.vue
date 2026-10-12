<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5nnmsbvd.css';
import '../../css/f/f3hc-8p1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m5nnmsbvd"/><path class="f3hc-8p1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:stamp-stroke-20" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2vfikbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k2vfikbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scaleway-dark" /></template>

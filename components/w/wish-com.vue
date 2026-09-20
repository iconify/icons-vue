<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyf7383ma.css';
import '../../css/o/o703l3o2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nyf7383ma"/><path class="o703l3o2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wish-com" /></template>

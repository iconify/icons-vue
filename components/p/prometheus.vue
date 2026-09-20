<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcjzopqyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wcjzopqyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:prometheus" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1-96opxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c1-96opxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:swarmpit-light" /></template>

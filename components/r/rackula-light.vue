<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzklfkbih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fzklfkbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rackula-light" /></template>

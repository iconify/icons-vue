<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6huf2bix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s6huf2bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:matter" /></template>

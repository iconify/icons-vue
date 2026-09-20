<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiipxcb8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xiipxcb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:prunemate-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6uzzfd-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g6uzzfd-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stump-light" /></template>

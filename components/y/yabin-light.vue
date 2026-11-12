<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymrr6abhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ymrr6abhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yabin-light" /></template>

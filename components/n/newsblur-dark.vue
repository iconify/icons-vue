<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4viabbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r4viabbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:newsblur-dark" /></template>

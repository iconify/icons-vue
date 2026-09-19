<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg82e8b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pg82e8b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:up-arrow-circle" /></template>

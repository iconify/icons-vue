<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d06squwrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d06squwrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:stats" /></template>

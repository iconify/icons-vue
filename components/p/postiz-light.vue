<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw2zm6rod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vw2zm6rod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:postiz-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7c2-v0mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d7c2-v0mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planning-center-registrations-light" /></template>

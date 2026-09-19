<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhc0pb2vu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":328,"height":512};
const content = `<path class="nhc0pb2vu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:watch" /></template>

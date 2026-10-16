<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6t-wwj2r.css';
import '../../css/c/cm_9ngbtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d6t-wwj2r"/><path class="cm_9ngbtm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:semi-detached-20" /></template>

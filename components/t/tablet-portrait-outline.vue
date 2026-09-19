<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv4wt1bhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="kv4wt1bhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:tablet-portrait-outline" /></template>

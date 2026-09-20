<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8zj8i1eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f8zj8i1eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nodecast-tv-light" /></template>

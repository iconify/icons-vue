<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq0-f_nih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rq0-f_nih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:searxng" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq7ek5b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rq7ek5b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rssrise-dark" /></template>

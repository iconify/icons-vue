<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orjwlbbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="orjwlbbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:photoprism-dark" /></template>

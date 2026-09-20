<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jg8870b6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jg8870b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:podcast-index" /></template>

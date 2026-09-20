<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z172f6bjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z172f6bjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nummo-dark" /></template>

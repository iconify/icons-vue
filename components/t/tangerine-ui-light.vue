<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g16ka0d3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g16ka0d3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tangerine-ui-light" /></template>

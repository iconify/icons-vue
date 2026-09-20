<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q30f-ac4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q30f-ac4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nodebb-dark" /></template>

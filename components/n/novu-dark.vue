<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtyemfz0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mtyemfz0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:novu-dark" /></template>

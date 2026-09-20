<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta4qt8blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ta4qt8blo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:obico" /></template>

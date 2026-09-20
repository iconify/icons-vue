<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di3lwkbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="di3lwkbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mqtt-dark" /></template>

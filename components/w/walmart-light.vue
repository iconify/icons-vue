<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjkqmbb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bjkqmbb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:walmart-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns55a6b6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ns55a6b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spacebar-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jan45d7nm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jan45d7nm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:owncast-light" /></template>

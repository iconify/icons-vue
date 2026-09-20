<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbirl8byl.css';
import '../../css/h/h546kdb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jbirl8byl"/><path class="h546kdb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rachio" /></template>

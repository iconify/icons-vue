<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/do5wwxbpa.css';
import '../../css/a/az6iwibpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="do5wwxbpa"/><path class="az6iwibpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:warpgate" /></template>

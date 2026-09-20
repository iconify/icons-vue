<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6lu45vzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e6lu45vzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:signal-light" /></template>

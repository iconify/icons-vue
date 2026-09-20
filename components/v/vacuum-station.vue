<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1pfnlbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a1pfnlbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:vacuum-station" /></template>

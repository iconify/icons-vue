<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah_305bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ah_305bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plane-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p45bg4ozx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p45bg4ozx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openleaf-light" /></template>

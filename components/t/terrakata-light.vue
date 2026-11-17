<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7xnxgbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a7xnxgbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:terrakata-light" /></template>

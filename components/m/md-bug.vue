<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7951cbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q7951cbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-bug" /></template>

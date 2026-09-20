<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qflkik2lo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qflkik2lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:matomo-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvg43muth.css';
import '../../css/h/hkazuhb3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kvg43muth"/><circle class="hkazuhb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:thermometer-outline" /></template>

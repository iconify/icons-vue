<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyh0s5bvl.css';
import '../../css/c/ciel5gbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dyh0s5bvl"/><path class="ciel5gbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wells-fargo" /></template>

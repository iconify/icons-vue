<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0uvq1byx.css';
import '../../css/h/hijad5bip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r0uvq1byx"/><path class="hijad5bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:storybook-light" /></template>

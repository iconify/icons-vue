<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egkkoob5g.css';
import '../../css/m/m9rpzdbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="egkkoob5g"/><path class="m9rpzdbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:storybook-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7llo2a6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="l7llo2a6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:ups" /></template>

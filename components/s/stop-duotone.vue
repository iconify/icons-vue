<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8jto1bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8jto1bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:stop-duotone" /></template>

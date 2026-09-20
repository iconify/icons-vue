<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghek0nbsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ghek0nbsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nginx-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k76k60btn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k76k60btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:remoteterm-dark" /></template>

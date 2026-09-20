<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8a2m6m6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p8a2m6m6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:onwatch-dark" /></template>

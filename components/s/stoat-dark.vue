<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl1k8xx3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bl1k8xx3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:stoat-dark" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs8thns5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qs8thns5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:photoprism-light" /></template>

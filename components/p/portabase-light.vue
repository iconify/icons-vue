<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln4zqubks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ln4zqubks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:portabase-light" /></template>

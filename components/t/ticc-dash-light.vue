<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9ypnhbge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c9ypnhbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ticc-dash-light" /></template>

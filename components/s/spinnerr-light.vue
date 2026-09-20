<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x81v4veyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x81v4veyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spinnerr-light" /></template>

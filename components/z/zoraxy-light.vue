<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei45d4g-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ei45d4g-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zoraxy-light" /></template>

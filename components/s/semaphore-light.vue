<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avrte1b7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="avrte1b7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:semaphore-light" /></template>

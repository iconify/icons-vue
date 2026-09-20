<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avdrmxbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="avdrmxbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planning-center-check-ins-dark" /></template>

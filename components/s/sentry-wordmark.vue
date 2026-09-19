<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3a964bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l3a964bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:sentry-wordmark" /></template>

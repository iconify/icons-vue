<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahtk07bbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ahtk07bbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:posthog-dark" /></template>

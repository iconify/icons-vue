<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df6bc1b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="df6bc1b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:verified-filled" /></template>

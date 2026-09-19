<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0rocyc2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s0rocyc2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:message-failed" /></template>

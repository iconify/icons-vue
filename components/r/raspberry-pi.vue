<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj8rmnbdx.css';
import '../../css/b/brx3lrbll.css';
import '../../css/q/qa-v84whg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qj8rmnbdx"/><path class="brx3lrbll"/><path class="qa-v84whg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:raspberry-pi" /></template>

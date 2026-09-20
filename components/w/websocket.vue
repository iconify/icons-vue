<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3w3uox9w.css';
import '../../css/j/j4n3fkkjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="s3w3uox9w"/><path class="j4n3fkkjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:websocket" /></template>

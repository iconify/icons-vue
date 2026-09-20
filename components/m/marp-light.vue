<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7ygtfbzr.css';
import '../../css/c/cqb6abcqd.css';
import '../../css/d/dcbk0ez8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f7ygtfbzr"/><path class="cqb6abcqd"/><path class="dcbk0ez8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:marp-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbrl8dbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pbrl8dbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:retroassembly-light" /></template>

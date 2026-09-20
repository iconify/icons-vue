<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw5h94i8m.css';
import '../../css/i/ingurx9qd.css';
import '../../css/u/u2ff1xk4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tw5h94i8m"/><path class="ingurx9qd"/><path class="u2ff1xk4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nightlio" /></template>

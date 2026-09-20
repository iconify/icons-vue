<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sotbp4b5s.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="sotbp4b5s"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:purple-flag" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwlpnt-mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bwlpnt-mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:tag" /></template>

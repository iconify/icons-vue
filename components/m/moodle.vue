<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztfe2y7ay.css';
import '../../css/u/u_faizb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ztfe2y7ay"/><path class="u_faizb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:moodle" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdzw-5b-o.css';
import '../../css/j/jx1563boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bdzw-5b-o"/><path class="jx1563boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:oneuptime" /></template>

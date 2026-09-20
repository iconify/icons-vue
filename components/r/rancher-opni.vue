<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7q30fbjm.css';
import '../../css/k/k42dqu5-u.css';
import '../../css/r/reokt-boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e7q30fbjm"/><path class="k42dqu5-u"/><path class="reokt-boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-opni" /></template>

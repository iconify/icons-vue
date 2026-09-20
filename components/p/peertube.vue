<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_64j2bck.css';
import '../../css/a/ao9inwbnl.css';
import '../../css/z/zduyjj29s.css';
import '../../css/m/mtc92wbsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j_64j2bck"/><path class="ao9inwbnl"/><path class="zduyjj29s"/><path class="mtc92wbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:peertube" /></template>

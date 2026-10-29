<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/d/d7496abza.css';
import '../../css/l/lrb2rmp9w.css';
import '../../css/a/aalr8-b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="d7496abza"/><path class="lrb2rmp9w wm-a"/><path class="aalr8-b6s wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:timer-off-solid" /></template>

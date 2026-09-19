<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/q/qek2tkbit.css';
import '../../css/w/wdnr6wb9s.css';
import '../../css/y/yqmv7tb2e.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGeVCSIbQW"><g class="s9cl3zbei"><rect class="qek2tkbit"/><path class="wdnr6wb9s"/><path class="yqmv7tb2e"/></g></mask></defs><path mask="url(#SVGeVCSIbQW)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:six-key" /></template>

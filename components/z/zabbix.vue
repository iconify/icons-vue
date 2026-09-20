<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4minvbuf.css';
import '../../css/i/i6s53x8dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x4minvbuf"/><path class="i6s53x8dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zabbix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luevgzb2b.css';
import '../../css/z/zrlocwb7c.css';
import '../../css/p/p7uzcdb2n.css';
import '../../css/y/ygtv74bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="luevgzb2b"/><path class="zrlocwb7c"/><path class="p7uzcdb2n"/><path class="ygtv74bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-farm-alert-48-bold" /></template>

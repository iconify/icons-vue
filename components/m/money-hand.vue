<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgckyq4_m.css';
import '../../css/s/sy9lcgb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qgckyq4_m"/><path class="sy9lcgb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:money-hand" /></template>

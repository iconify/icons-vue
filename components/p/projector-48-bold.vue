<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab8fc_wvr.css';
import '../../css/z/zd05-xlem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ab8fc_wvr"/><path class="zd05-xlem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:projector-48-bold" /></template>

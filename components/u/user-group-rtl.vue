<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4i99xbag.css';
import '../../css/y/yh894zb-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n4i99xbag"/><circle class="yh894zb-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:user-group-rtl" /></template>

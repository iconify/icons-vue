<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me00cjb6q.css';
import '../../css/d/dezr6ts0k.css';
import '../../css/w/wdholibql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="me00cjb6q"/><path class="dezr6ts0k"/><path class="wdholibql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:vue-config" /></template>

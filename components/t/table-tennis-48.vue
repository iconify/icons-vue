<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytknsibzh.css';
import '../../css/v/vr1h12b6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ytknsibzh"/><path class="vr1h12b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:table-tennis-48" /></template>

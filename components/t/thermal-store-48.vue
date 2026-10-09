<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlgr2s59b.css';
import '../../css/s/s1z91sb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xlgr2s59b"/><path class="s1z91sb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermal-store-48" /></template>

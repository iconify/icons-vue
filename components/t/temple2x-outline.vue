<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hss7wl3yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hss7wl3yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:temple2x-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apb_dgbpm.css';
import '../../css/v/vw3o48bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="apb_dgbpm"/><path class="vw3o48bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:microgrid-48-bold" /></template>

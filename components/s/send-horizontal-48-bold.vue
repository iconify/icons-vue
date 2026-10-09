<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np--nab8s.css';
import '../../css/b/b31s_0bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="np--nab8s"/><path class="b31s_0bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:send-horizontal-48-bold" /></template>

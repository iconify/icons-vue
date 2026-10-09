<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrk88uxja.css';
import '../../css/a/aoqq0ebdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qrk88uxja"/><path class="aoqq0ebdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-right-48-bold" /></template>

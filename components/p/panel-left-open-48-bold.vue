<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9a09orqa.css';
import '../../css/x/xklhocbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q9a09orqa"/><path class="xklhocbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-left-open-48-bold" /></template>

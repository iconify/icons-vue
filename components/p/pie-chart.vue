<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7dwa2e_z.css';
import '../../css/w/wd-20gb_a.css';
import '../../css/g/gzv9kc5wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t7dwa2e_z"/><path class="wd-20gb_a"/><path class="gzv9kc5wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:pie-chart" /></template>

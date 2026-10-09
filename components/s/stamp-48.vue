<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1m2c5x5x.css';
import '../../css/z/zxs4re9vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l1m2c5x5x"/><path class="zxs4re9vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stamp-48" /></template>

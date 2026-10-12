<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbqw8r0sh.css';
import '../../css/r/r_zfy8bnu.css';
import '../../css/q/qpbeuubxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wbqw8r0sh"/><path class="r_zfy8bnu"/><path class="qpbeuubxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:split-48" /></template>

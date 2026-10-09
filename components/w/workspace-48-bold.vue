<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qeucaqz1x.css';
import '../../css/q/qexfecbci.css';
import '../../css/m/m_2yb9bfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qeucaqz1x"/><path class="qexfecbci"/><path class="m_2yb9bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:workspace-48-bold" /></template>

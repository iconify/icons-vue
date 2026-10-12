<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6q-m_77w.css';
import '../../css/l/l__xd22cd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q6q-m_77w"/><path class="l__xd22cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:protractor-48-bold" /></template>

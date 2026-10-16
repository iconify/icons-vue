<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty5a_vbpt.css';
import '../../css/i/iiw5x-k7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ty5a_vbpt"/><path class="iiw5x-k7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-left-open-48" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddstmrebw.css';
import '../../css/x/xjh2b-bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ddstmrebw"/><path class="xjh2b-bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wifi-medium-48" /></template>

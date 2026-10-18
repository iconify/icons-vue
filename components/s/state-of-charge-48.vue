<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rplblqbon.css';
import '../../css/n/nlh68myqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rplblqbon"/><path class="nlh68myqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:state-of-charge-48" /></template>

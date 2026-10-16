<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp-qlgb3c.css';
import '../../css/u/uw0hg1f1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kp-qlgb3c"/><path class="uw0hg1f1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ratchet-48" /></template>

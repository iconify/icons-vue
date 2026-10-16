<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx_rtncis.css';
import '../../css/e/e0nmxkmog.css';
import '../../css/y/y9mg2tbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mx_rtncis"/><path class="e0nmxkmog"/><path class="y9mg2tbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:server-check-48-bold" /></template>

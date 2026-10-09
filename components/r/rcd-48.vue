<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp-8xbcar.css';
import '../../css/l/luu7bn_8g.css';
import '../../css/b/btws7t3pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mp-8xbcar"/><path class="luu7bn_8g"/><path class="btws7t3pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rcd-48" /></template>

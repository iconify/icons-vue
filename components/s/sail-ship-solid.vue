<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izs_rbb_s.css';
import '../../css/p/pt6hrq4xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="izs_rbb_s"/><path class="pt6hrq4xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:sail-ship-solid" /></template>

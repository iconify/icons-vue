<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai_jqqbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ai_jqqbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:navigation" /></template>

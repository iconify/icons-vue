<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmxtxk5go.css';
import '../../css/o/ofbjwwbcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xmxtxk5go"/><path class="ofbjwwbcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:visio-meet" /></template>

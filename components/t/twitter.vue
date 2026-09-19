<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d476gw_ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d476gw_ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:twitter" /></template>

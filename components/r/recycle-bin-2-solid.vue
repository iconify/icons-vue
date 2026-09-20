<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cditb06mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="cditb06mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:recycle-bin-2-solid" /></template>

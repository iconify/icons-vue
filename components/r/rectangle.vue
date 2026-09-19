<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2ok4bcnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d2ok4bcnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:rectangle" /></template>

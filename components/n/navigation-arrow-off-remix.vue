<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq4s77gph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lq4s77gph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:navigation-arrow-off-remix" /></template>

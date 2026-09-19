<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evvbtj-xi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="evvbtj-xi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:yep" /></template>

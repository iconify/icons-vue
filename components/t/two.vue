<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0gllcbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a0gllcbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:two" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4ko2it3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b4ko2it3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:navigation" /></template>

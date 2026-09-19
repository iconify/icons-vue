<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjmja5ggc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yjmja5ggc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:pinwheel" /></template>

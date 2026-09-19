<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stirrtb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="stirrtb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:pot" /></template>

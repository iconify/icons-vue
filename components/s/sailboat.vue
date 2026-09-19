<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5vz3hbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v5vz3hbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sailboat" /></template>

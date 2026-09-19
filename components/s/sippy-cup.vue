<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz8pd-b6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bz8pd-b6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sippy-cup" /></template>

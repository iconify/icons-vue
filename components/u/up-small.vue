<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukkq_py3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ukkq_py3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:up-small" /></template>

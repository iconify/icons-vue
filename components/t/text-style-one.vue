<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvbo2fx7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xvbo2fx7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:text-style-one" /></template>

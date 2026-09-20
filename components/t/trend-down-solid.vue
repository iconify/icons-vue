<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbtm4g3rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="hbtm4g3rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:trend-down-solid" /></template>

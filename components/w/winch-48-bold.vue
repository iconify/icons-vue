<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpxr-ob7u.css';
import '../../css/v/v7-g3_bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wpxr-ob7u"/><path class="v7-g3_bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:winch-48-bold" /></template>

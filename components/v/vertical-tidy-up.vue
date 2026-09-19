<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aosqt_h4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aosqt_h4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:vertical-tidy-up" /></template>

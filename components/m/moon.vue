<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yojm6_ddd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yojm6_ddd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:moon" /></template>

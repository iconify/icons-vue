<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dup5dmb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dup5dmb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:pangle" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oftl5vb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oftl5vb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:system" /></template>

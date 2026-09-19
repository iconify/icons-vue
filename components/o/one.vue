<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz7e0qnyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nz7e0qnyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:one" /></template>

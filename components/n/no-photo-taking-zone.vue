<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp-8ehbzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bp-8ehbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:no-photo-taking-zone" /></template>

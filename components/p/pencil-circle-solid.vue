<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp-6ekjhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xp-6ekjhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pencil-circle-solid" /></template>

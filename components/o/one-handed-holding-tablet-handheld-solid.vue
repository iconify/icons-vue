<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n550um41m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="n550um41m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:one-handed-holding-tablet-handheld-solid" /></template>

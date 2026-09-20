<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx03hvb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zx03hvb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:reset-clock-solid" /></template>

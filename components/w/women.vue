<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2x2-mbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l2x2-mbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:women" /></template>

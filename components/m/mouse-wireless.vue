<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohkgcchcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ohkgcchcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:mouse-wireless" /></template>

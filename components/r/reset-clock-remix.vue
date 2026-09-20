<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfdy5f7yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lfdy5f7yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:reset-clock-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woewqwmtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="woewqwmtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:slack" /></template>

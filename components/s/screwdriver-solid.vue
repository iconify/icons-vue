<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9m6ewbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="p9m6ewbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:screwdriver-solid" /></template>

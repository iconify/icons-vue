<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp66xwspr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="tp66xwspr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:radioactive-1-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6y15mb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j6y15mb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:park-solid" /></template>

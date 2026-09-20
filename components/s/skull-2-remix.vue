<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrnc2rbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rrnc2rbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:skull-2-remix" /></template>

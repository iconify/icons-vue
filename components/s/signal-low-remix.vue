<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj9wi1brp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vj9wi1brp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:signal-low-remix" /></template>

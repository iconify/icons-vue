<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/diq48hb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="diq48hb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:zoom-in-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm528p0go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fm528p0go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:rss-square-solid" /></template>

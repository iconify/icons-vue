<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/burs33b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="burs33b6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:two-semicircles" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa9-8fuis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aa9-8fuis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:paragraph-break-two" /></template>

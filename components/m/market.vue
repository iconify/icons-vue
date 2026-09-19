<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvq1evy_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jvq1evy_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:market" /></template>

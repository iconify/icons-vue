<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs_17i3uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fs_17i3uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:twitter" /></template>

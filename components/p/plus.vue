<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7zs8cblv.css';
import '../../css/p/p8zognblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7zs8cblv"/><path class="p8zognblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:plus" /></template>

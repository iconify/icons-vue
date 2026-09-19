<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smw7apbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="smw7apbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:text-rotation-up" /></template>

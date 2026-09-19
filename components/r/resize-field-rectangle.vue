<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl308bbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl308bbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:resize-field-rectangle" /></template>

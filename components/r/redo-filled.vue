<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkf6x8b6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gkf6x8b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:redo-filled" /></template>

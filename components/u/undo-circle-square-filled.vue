<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l25s7qq7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l25s7qq7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:undo-circle-square-filled" /></template>

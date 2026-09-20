<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6c0kwmfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e6c0kwmfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:rewind-15s" /></template>

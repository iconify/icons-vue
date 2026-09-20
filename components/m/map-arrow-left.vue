<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5fs8vb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l5fs8vb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:map-arrow-left" /></template>

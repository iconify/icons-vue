<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbjprlb4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jbjprlb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:tag3-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4hxffrur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="i4hxffrur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:record-filled" /></template>

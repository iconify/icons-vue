<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waor1ybrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="waor1ybrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:undo-circle" /></template>

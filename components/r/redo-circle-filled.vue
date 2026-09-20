<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7ryqgg0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o7ryqgg0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:redo-circle-filled" /></template>

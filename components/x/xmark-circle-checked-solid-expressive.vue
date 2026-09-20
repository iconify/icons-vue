<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg3wixb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dg3wixb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:xmark-circle-checked-solid-expressive" /></template>

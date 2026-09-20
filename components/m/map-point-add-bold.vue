<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcbw4qbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jcbw4qbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-add-bold" /></template>

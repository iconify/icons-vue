<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v40_13maw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v40_13maw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:wbt" /></template>

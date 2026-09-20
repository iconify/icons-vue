<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hoo2owbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hoo2owbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:refresh-outline" /></template>

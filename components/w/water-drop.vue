<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ffcd2bc3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ffcd2bc3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:water-drop" /></template>

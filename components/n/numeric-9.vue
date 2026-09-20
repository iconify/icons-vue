<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y38-9crzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y38-9crzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-9" /></template>

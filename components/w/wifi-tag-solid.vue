<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbt5gzewv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jbt5gzewv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:wifi-tag-solid" /></template>

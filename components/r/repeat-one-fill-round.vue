<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln0v0fbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln0v0fbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:repeat-one-fill-round" /></template>

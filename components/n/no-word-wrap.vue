<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gar7pzrar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gar7pzrar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:no-word-wrap" /></template>

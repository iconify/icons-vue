<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb03xai3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jb03xai3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-x-sharp-fill" /></template>

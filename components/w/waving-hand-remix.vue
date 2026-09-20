<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4oochb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j4oochb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:waving-hand-remix" /></template>

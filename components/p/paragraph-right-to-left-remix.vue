<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6e5euaej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a6e5euaej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:paragraph-right-to-left-remix" /></template>

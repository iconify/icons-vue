<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8f-i9b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j8f-i9b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:paragraph-right-to-left-solid" /></template>

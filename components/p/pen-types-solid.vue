<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6bhd7jxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6bhd7jxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pen-types-solid" /></template>

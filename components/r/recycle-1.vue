<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyo2u0bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyo2u0bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:recycle-1" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3i5zubvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q3i5zubvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tablet-sharp-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2c3j48yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v2c3j48yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:test-tube-remix" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynj00dlie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ynj00dlie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sleigh-fill" /></template>

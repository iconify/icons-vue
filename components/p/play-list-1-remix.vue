<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r21_olbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r21_olbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:play-list-1-remix" /></template>

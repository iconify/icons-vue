<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihfwy-njj.css';
import '../../css/v/v2nlyobhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihfwy-njj"/><path class="v2nlyobhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:writing" /></template>

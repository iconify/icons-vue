<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu8amwuqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="fu8amwuqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:paperclip-1" /></template>

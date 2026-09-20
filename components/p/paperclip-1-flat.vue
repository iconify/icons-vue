<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r88f92b7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r88f92b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:paperclip-1-flat" /></template>

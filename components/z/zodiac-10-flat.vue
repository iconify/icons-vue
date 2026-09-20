<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn6g75bba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kn6g75bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:zodiac-10-flat" /></template>

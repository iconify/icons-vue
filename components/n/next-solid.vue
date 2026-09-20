<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s34m4uamv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s34m4uamv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:next-solid" /></template>

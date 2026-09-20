<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw6d_2bsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fw6d_2bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:phone-ringing-1-solid" /></template>

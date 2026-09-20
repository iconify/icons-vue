<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orjk9nbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="orjk9nbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:paperclip-1-solid" /></template>

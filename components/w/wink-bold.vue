<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt9639byu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="tt9639byu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:wink-bold" /></template>

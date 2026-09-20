<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzz853bhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hzz853bhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:megaphone-1-remix" /></template>

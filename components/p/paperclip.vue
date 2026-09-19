<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3-tx0tsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="y3-tx0tsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:paperclip" /></template>

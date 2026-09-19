<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owim25iry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="owim25iry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ship-outline" /></template>

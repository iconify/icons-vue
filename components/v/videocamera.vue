<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td7o5qxkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="td7o5qxkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:videocamera" /></template>

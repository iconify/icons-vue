<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u73_7tktp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="u73_7tktp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:question-mark" /></template>

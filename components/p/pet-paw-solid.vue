<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ystvwxwrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ystvwxwrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pet-paw-solid" /></template>

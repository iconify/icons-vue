<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrbsh4b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yrbsh4b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:xbox-solid" /></template>

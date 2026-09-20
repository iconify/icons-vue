<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ach9e5bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ach9e5bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:terminal-screen-with-hash-prompt" /></template>

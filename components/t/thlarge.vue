<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nimvi2b3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="nimvi2b3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:thlarge" /></template>

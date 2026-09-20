<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixc7s1b4e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ixc7s1b4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:shapes-filled" /></template>

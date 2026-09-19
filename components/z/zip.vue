<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrntv9boe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="qrntv9boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:zip" /></template>

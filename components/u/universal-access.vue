<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i72_afoiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="i72_afoiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:universal-access" /></template>

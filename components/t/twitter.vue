<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk80sglnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":830,"height":810};
const content = `<path class="mk80sglnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:twitter" /></template>

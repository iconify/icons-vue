<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwepd2fyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="fwepd2fyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:tablet" /></template>

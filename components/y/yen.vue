<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfh81vbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":769,"height":1024};
const content = `<path class="cfh81vbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:yen" /></template>

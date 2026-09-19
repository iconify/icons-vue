<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0bm4bcod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z0bm4bcod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:wacom" /></template>

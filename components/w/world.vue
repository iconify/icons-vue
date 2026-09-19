<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-0k5mg3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u-0k5mg3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:world" /></template>

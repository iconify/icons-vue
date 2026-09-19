<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cunm7x32u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cunm7x32u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:sort-up" /></template>

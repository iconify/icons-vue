<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/utc4rgqvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="utc4rgqvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pencil" /></template>

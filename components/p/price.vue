<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4kr70i4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1023};
const content = `<path class="l4kr70i4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:price" /></template>

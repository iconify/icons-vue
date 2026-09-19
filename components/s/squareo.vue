<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8e67yy6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="f8e67yy6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squareo" /></template>

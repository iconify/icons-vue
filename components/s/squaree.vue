<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpy1pv5sj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="vpy1pv5sj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squaree" /></template>

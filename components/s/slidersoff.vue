<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv9d3zbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gv9d3zbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:slidersoff" /></template>

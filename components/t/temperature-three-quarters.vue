<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loxnei52m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="loxnei52m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:temperature-three-quarters" /></template>

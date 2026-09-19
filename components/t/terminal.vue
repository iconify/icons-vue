<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvs_bezwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="lvs_bezwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:terminal" /></template>

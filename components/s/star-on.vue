<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrj54obkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lrj54obkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:star-on" /></template>

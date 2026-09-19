<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-fn4_ybf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="g-fn4_ybf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:trash-alt" /></template>

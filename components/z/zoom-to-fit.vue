<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmt6jqxhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vmt6jqxhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:zoom-to-fit" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3vhyqp0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="o3vhyqp0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:picasa" /></template>

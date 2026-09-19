<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1g2ogzoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="y1g2ogzoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:person-half-dress" /></template>

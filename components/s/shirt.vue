<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1yv8q47l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1yv8q47l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:shirt" /></template>

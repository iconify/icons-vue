<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0tnvacgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="y0tnvacgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:thumbtack" /></template>

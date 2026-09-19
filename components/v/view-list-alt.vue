<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikrlaw81o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="ikrlaw81o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:view-list-alt" /></template>

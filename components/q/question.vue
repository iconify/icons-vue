<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1nxs9bli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="p1nxs9bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:question" /></template>

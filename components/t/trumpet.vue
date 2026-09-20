<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk593vdev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sk593vdev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:trumpet" /></template>

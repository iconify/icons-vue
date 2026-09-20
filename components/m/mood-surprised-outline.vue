<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxmwplbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gxmwplbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:mood-surprised-outline" /></template>

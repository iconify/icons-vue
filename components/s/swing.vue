<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p__2-wbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p__2-wbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:swing" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3ptjyb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o3ptjyb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sailboat" /></template>

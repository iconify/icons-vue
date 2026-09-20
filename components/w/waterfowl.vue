<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfg9cb5pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pfg9cb5pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:waterfowl" /></template>

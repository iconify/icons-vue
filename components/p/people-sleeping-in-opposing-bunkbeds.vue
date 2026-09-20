<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dup2ybc4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dup2ybc4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:people-sleeping-in-opposing-bunkbeds" /></template>

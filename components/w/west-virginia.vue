<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whvnh9-te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="whvnh9-te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:west-virginia" /></template>

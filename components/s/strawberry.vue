<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esom1xbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":961};
const content = `<path class="esom1xbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:strawberry" /></template>
